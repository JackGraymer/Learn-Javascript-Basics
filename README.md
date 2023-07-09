# Learn-Javascript-Basics
## by Nathan Sebhastian 

<br>

![Learn JavaScript for Beginners – JS Basics Handbook](https://www.freecodecamp.org/news/content/images/size/w2000/2023/06/book-cover.jpg)     


                            
<h3>The goal of this handbook is to quickly introduce you to the basics of JavaScript so you can start programming applications.</h3>
<p>Instead of covering all the theories and concepts of JavaScript, I'll be teaching you only the most important building blocks of the language. We'll cover things like variables, data types, functions, objects, arrays, and classes. You'll also learn how to mix them all to build a small but solid program.</p>
<p>We're also going to leave out HTML, CSS, and using JavaScript in the browser. This tutorial focuses only on JavaScript as a programming language and uses the terminal to run the code.</p>
<p>This tutorial also has exercises for each section which gives you time to practice what you learned and "drill" the knowledge into your brain.</p>
<p>This handbook is completely free right here in this webpage. If you want the <a href="https://codewithnathan.com/js-course">PDF and EPUB version of this tutorial</a>, you can pay a small fee for it. It'll help support me in creating an in-depth JavaScript Tutorial that will help you build a complete web application.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="tableofcontents">Table of Contents</h2>
<ul>
<li><a href="#1javascriptintroduction">1 - JavaScript Introduction</a>
<ul>
<li><a href="#whylearnjavascript">Why learn JavaScript</a></li>
<li><a href="#javascriptvsjava">JavaScript vs Java</a></li>
</ul>
</li>
<li><a href="#2howtosetupyourcomputer">2 - How to Set Up Your Computer</a>
<ul>
<li><a href="#howtoinstallvscode">How to Install VSCode</a></li>
<li><a href="#howtoinstallnodejs">How to Install Node.js</a></li>
</ul>
</li>
<li><a href="#3quickconsoleintroduction">3 - Quick Console Introduction</a></li>
<li><a href="#4timetosayhelloworld">4 - Time to Say Hello World!</a></li>
<li><a href="#5javascriptcodestructure">5 - JavaScript Code Structure</a>
<ul>
<li><a href="#statements">Statements</a></li>
<li><a href="#comments">Comments</a></li>
<li><a href="#executionflow">Execution Flow</a></li>
<li><a href="#exercise1">Exercise #1</a></li>
</ul>
</li>
<li><a href="#6javascriptvariables">6 - JavaScript Variables</a>
<ul>
<li><a href="#variablenaming">Variable naming</a></li>
<li><a href="#constantvariable">Constant variable</a></li>
<li><a href="#thevarkeyword">The var keyword</a></li>
<li><a href="#exercise2">Exercise #2</a></li>
<li><a href="#summary">Summary</a></li>
</ul>
</li>
<li><a href="#7javascriptbasicdatatypes">7 - JavaScript Basic Data Types</a>
<ul>
<li><a href="#stringsinjavascript">Strings in JavaScript</a></li>
<li><a href="#numbersintegersandfloatsinjavascript">Numbers (integers and floats) in JavaScript</a></li>
<li><a href="#booleansinjavascript">Booleans in JavaScript</a></li>
<li><a href="#undefinedinjavascript">Undefined in JavaScript</a></li>
<li><a href="#nullinjavascript">Null in JavaScript</a></li>
</ul>
</li>
<li><a href="#8typeconversionandcoercion">8 - Type conversion and coercion</a>
<ul>
<li><a href="#typecoercion">Type coercion</a></li>
<li><a href="#typecoercionrules">Type coercion rules</a></li>
<li><a href="#whyyoushouldavoidtypecoercion">Why you should avoid type coercion</a></li>
</ul>
</li>
<li><a href="#9operatorsinjavascript">9 - Operators in JavaScript</a>
<ul>
<li><a href="#arithmeticoperators">Arithmetic operators</a></li>
<li><a href="#theassignmentoperator">The assignment operator</a></li>
<li><a href="#thecomparisonoperators">The comparison operators</a></li>
<li><a href="#logicaloperators">Logical operators</a></li>
<li><a href="#thetypeofoperator">The typeof operator</a></li>
<li><a href="#exercise3">Exercise #3</a></li>
</ul>
</li>
<li><a href="#10javascriptarrays">10 - JavaScript Arrays</a>
<ul>
<li><a href="#arrayindexposition">Array index position</a></li>
<li><a href="#specialmethodsforarraymanipulation">Special methods for array manipulation</a></li>
<li><a href="#exercise4">Exercise #4</a></li>
</ul>
</li>
<li><a href="#11controlflowsconditionalsinjavascript">11 - Control Flows (Conditionals) in JavaScript</a>
<ul>
<li><a href="#theifelsestatement">The if...else statement</a></li>
<li><a href="#theswitchcasestatement">The switch...case statement</a></li>
<li><a href="#theswitchstatementbody">The switch statement body</a></li>
<li><a href="#switchstatementusecases">Switch statement use cases</a></li>
<li><a href="#exercise5">Exercise #5</a></li>
</ul>
</li>
<li><a href="#12controlflowsloopsinjavascript">12 - Control Flows (Loops) in JavaScript</a>
<ul>
<li><a href="#theforstatement">The for statement</a></li>
<li><a href="#whentousetheforloop">When to use the for loop?</a></li>
<li><a href="#thewhilestatement">The while statement</a></li>
<li><a href="#whentousethewhileloop">When to use the while loop?</a></li>
<li><a href="#exercise6">Exercise #6</a></li>
</ul>
</li>
<li><a href="#13functionsinjavascript">13 - Functions in JavaScript</a>
<ul>
<li><a href="#howtocreateyourownfunction">How to create your own function</a></li>
<li><a href="#functionparametersandarguments">Function parameters and arguments</a></li>
<li><a href="#defaultparameters">Default parameters</a></li>
<li><a href="#defaultparametersandnull">Default parameters and null</a></li>
<li><a href="#thereturnstatement">The return statement</a></li>
<li><a href="#variablescope">Variable scope</a></li>
<li><a href="#therestparameter">The rest parameter</a></li>
<li><a href="#arrowfunction">Arrow function</a></li>
<li><a href="#singleandmultilinearrowfunctions">Single and multiline arrow functions</a></li>
<li><a href="#arrowfunctionwithoutroundbrackets">Arrow function without round brackets</a></li>
<li><a href="#arrowfunctiondoesnthaveargumentsbinding">Arrow function doesn't have arguments binding</a></li>
<li><a href="#howtoconvertanormalfunctiontoanarrowfunctioneasily">How to convert a normal function to an arrow function easily</a></li>
<li><a href="#exercise7">Exercise #7</a></li>
</ul>
</li>
<li><a href="#14objectsinjavascript">14 - Objects in JavaScript</a>
<ul>
<li><a href="#howtoaccessobjectvalues">How to access object values</a></li>
<li><a href="#howtoaddanewpropertytotheobject">How to add a new property to the object</a></li>
<li><a href="#howtomodifyobjectproperties">How to modify object properties</a></li>
<li><a href="#howtodeletegobjectproperties">How to delete object properties</a></li>
<li><a href="#howtocheckifapropertyexistsinanobject">How to check if a property exists in an object</a></li>
<li><a href="#exercise8">Exercise #8</a></li>
</ul>
</li>
<li><a href="#finalexercisebuildeacashregistermachine">Final Exercise: Build a Cash Register Machine</a></li>
<li><a href="#conclusion">Conclusion</a></li>
<li><a href="#solutions">Solutions</a></li>
</ul>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="1javascriptintroduction">1 - JavaScript Introduction</h2>
<p>JavaScript was created around April 1995 by Brendan Eich. At the time, he was working to develop a browser for a company called Netscape. He was told that he only had 10 days to design and code a working prototype of a programming language that could run on the browser.</p>
<p>He needed to create a language that appealed to non-professional programmers like Microsoft Visual Basic.</p>
<p>The reason he was given only 10 days was that Netscape needed to release its browser, which at the time was in competition with  Microsoft.</p>
<p>In the beginning, JavaScript was not as powerful as it is today, since it was originally designed to add interaction and animation for web pages. It wasn't until 2005 when jQuery and AJAX were released that JavaScript began to be used in every website.</p>
<p>People simply didn't have an easy alternative to jQuery and AJAX for DOM manipulation and sending asynchronous requests. Plus, an active community of JavaScript developers kept adding new features to the library.</p>
<p>Then Google launched its modern Chrome browser, and Facebook started getting more people online. JavaScript began to grow to accomodate the ambitions of these giant internet companies.</p>
<p>Browsers began developing APIs that you could use in JavaScript. JS could retrieve information such as IP addresses and geographic locations from the browser, adding more power to internet companies to localize the features of their websites.</p>
<p>Then another innovation happened to make JavaScript even more powerful.</p>
<p>A server-side environment named Node.js was released in 2009, allowing JavaScript to run on the server side like PHP, Java, Python, Ruby, and many more. It also enabled devs to develop full-stack web applications using only JavaScript.</p>
<p>Today, JavaScript is a language that can power the web, desktop, and mobile applications.</p>
<p>Here's a quote from Tim O'Reilly, the founder of O'Reilly Media:</p>
<blockquote>
<p>Learning JavaScript used to mean you weren't a serious developer. Today, not learning JavaScript means the same thing.</p>
</blockquote>
<p>Learning JavaScript is now critical for people who want to be web developers.</p>
<h3 id="whylearnjavascript">Why learn JavaScript?</h3>
<p>There are 4 good reasons why you need to learn and deeply understand JavaScript:</p>
<ol>
<li>JavaScript is the only language that works in the browser</li>
<li>It's fairly easy to learn (but hard to master)</li>
<li>It's an essential language for making web applications</li>
<li>There are many career opportunities for JavaScript devs</li>
</ol>
<p>Learning JavaScript opens tremendous opportunities where you can be a frontend, backend, or mobile developer.</p>
<p>Basically, learning JavaScript is a gateway to career improvements in tech.</p>
<h3 id="javascriptvsjava">JavaScript vs Java</h3>
<p>In the beginning, JavaScript was actually named LiveScript. It was renamed to JavaScript because Java was a very popular programming language.</p>
<p>Since most software developers were already familiar with Java, the name JavaScript was thought to help in marketing JavaScript as a great programming language and draw the interest of developers at the time.</p>
<p>Just to be clear, JavaScript and Java are two completely different programming languages. You don't need to know Java to learn JavaScript (or the other way around). :)</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="2howtosetupyourcomputer">2 - How to Set Up Your Computer</h2>
<p>To write a program using JavaScript, you need to install 2 free tools that are available for all operating systems.</p>
<p>The first tool to install is Visual Studio Code.</p>
<h3 id="howtoinstallvscode">How to Install VSCode</h3>
<p>Visual Studio Code or VSCode for short is a text editor program created for the purpose of writing code. Aside from being free, VSCode is open source and available on all major operating systems.</p>
<p>You can use VSCode on Windows, macOS, and Linux, so if you don't have a text editor on your computer, I recommend that you install VSCode here.</p>
<p>Now that you have a text editor to write JavaScript code, you need a software to run JavaScript code. Let's install Node.js next.</p>
<h3 id="howtoinstallnodejs">How to Install Node.js</h3>
<p>To run JavaScript outside of the browser, you need to install Node.js, which is essentially a JavaScript runner.</p>
<p>Simply go to the Node.js website at nodejs.org and download the latest LTS version for your computer. Once the download is complete, install it on your system.</p>
<p>You need to run Node.js using the console, so open your command line or terminal application and run the following command:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">node</span> <span class="token parameter variable">-v</span>
</code></pre>
<p>This command will output the version of your freshly installed Node.js into the console.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="3quickconsoleintroduction">3 - Quick Console Introduction</h2>
<p>The console is a text-based interface that you can use to type and run commands on your computer. On Windows, it's called the Command Line. On macOS and Linux it's known as the Terminal.</p>
<p>You're not going to use all the commands available within the console. In fact, you only need to know 7 basic commands to help you run JavaScript code.</p>
<p>First, open the console program on your computer and type the <code>pwd</code> command:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token builtin class-name">pwd</span>
</code></pre>
<p>This is the command you use to find out which directory your terminal is currently on. <code>pwd</code> is short for print working directory.</p>
<p>To change the working directory, you need to run the <code>cd</code> command.</p>
<p>Here's an example to move into a child directory:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token builtin class-name">cd</span> directory_name/directory_name
</code></pre>
<p>To move up to a parent directory, you specify <code>..</code> next to the command:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token builtin class-name">cd</span> <span class="token punctuation">..</span>
</code></pre>
<p>To go up more than one directory, use <code>../..</code></p>
<p>To clear your console from previous commands and output, use the <code>clear</code> command:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">clear</span>
</code></pre>
<p>To print out the list of files and directories in the current directory, run the <code>ls</code> command:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">ls</span>
</code></pre>
<p>To create a new file, use the <code>touch</code> command followed by the file name and extension:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">touch</span> index.js
</code></pre>
<p>The command above will create a new JavaScript file named <code>index.js</code> on the current working directory.</p>
<p>To create a new directory, use the <code>mkdir</code> command followed by the directory name:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">mkdir</span> my_project
</code></pre>
<p>To run JavaScript using Node.js, specify <code>node</code> followed by the file name as follows:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">node</span> index.js
</code></pre>
<p>You'll see any output from the code in the same console.</p>
<p>There are lots of things you can do with the console, but these 7 commands would be enough because we only need it to run JavaScript code.</p>
<p>Next, let's run your first JavaScript program!</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="4timetosayhelloworld">4 - Time to Say Hello World!</h2>
<p>It's time to run your first JavaScript program using Node.</p>
<p>From the console, create a new JavaScript file named <code>index.js</code> using the <code>touch</code> command.</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">touch</span> index.js
</code></pre>
<p>Next, open the file using VSCode and write the following line of code into the file:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Back on the console, run this script with Node:</p>
<pre class="language-sh" tabindex="0"><code class="language-sh"><span class="token function">node</span> index.js
</code></pre>
<p>The console should execute the <code>index.js</code> file and print "Hello World!".</p>
<p>You've just run your very first JavaScript program using Node.js. Excellent!</p>
<p>When you run the <code>node index.js</code> command, the Node.js program starts reading the script line by line from top to bottom.</p>
<p>The <code>node</code> program sees that you wrote the word <code>console.log</code> followed by parentheses <code>()</code>, so it knows that you're instructing it to print something. The program then reads what you put in the parentheses and prints it out on the console.</p>
<p>In your VSCode or other text editor program, you should see different parts of your code highlighted with different colors. This is a feature of the text editor called <em>syntax highlighting</em>, and it's really useful to help you distinguish different parts of the code.</p>
<p>The <code>log</code> keyword is a function, so it gets highlighted in one color, while the words in the parentheses have another color.</p>
<p>A function is simply a piece of code that's used to perform a certain task. The <code>log()</code> function is used to "print" whatever you put inside the parentheses.</p>
<p>On the other hand, the <code>console</code> keyword is an object, which is a standalone property that gives access to certain functionalities.</p>
<p>We'll learn more about functions and objects later. For now, just remember that the <code>console.log()</code> keyword is used to print things to the console.</p>
<p>Next, let's start with learning JavaScript code structure.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="5javascriptcodestructure">5 - JavaScript Code Structure</h2>
<p>A computer program is a series of pieces of code written in a text file. These text files are then run through a software that's designed specially for running the code. The Node.js software you downloaded previously is the tool that processes JavaScript code.</p>
<p>Before we go further, let's understand the structure of code.</p>
<h3 id="statements">Statements</h3>
<p>A statement is a single instruction for the computer to run. Think of it like a sentence, but for computers. We can end a statement by using a semicolon <code>;</code> just like we can end a sentence using a dot <code>.</code></p>
<p>You can write multiple statements in a single line, but the convention is to write one statement per line:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// This is hard to read</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"I'm learning JavaScript"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Now it's better</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"I'm learning JavaScript"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Each statement is an expression of some action that needs to be carried out by the software that executes the code.</p>
<h3 id="comments">Comments</h3>
<p>In programming, comments are text we use to communicate the context of the code written in the file.</p>
<p>To write a comment in JavaScript, you need to add two forward slashes <code>//</code> before the comment as shown below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// This is a comment</span>
<span class="token comment">// This is also a comment</span>

<span class="token comment">// Below print two lines of statements</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"I'm learning JavaScript"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Comments are ignored by the language processor, so you can use comments to disable some code without having to delete that code.</p>
<p>The code below shows how to disable the second print statement:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// console.log("I'm learning JavaScript");</span>
</code></pre>
<h3 id="executionflow">Execution Flow</h3>
<p>A language processor such as Node.js executes statements in a top-down approach. The statement written in the first line will be executed before the second line, then continue down to the last line:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"I'm learning JavaScript"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Printing numbers</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello World!
I'm learning JavaScript
1
2
3
</code></pre>
<p>If you want to print the numbers before the text, then you need to move the corresponding <code>console.log()</code> lines to the top.</p>
<h3 id="exercise1">Exercise #1</h3>
<p>Try to print your name, age, and occupation on the console.</p>
<p>The output would look as follows:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">John Doe
19
Student
</code></pre>
<p>Now that you understand the basic code structure of JavaScript, let's continue with learning variables next.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="6javascriptvariables">6 - JavaScript Variables</h2>
<p>Before explaining what a variable is, I want you to change the code you've written in the <code>index.js</code> file.</p>
<p>Change the code in that file as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello World!"</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>message<span class="token punctuation">)</span>
</code></pre>
<p>Next, run the code using the <code>node index.js</code> command. You'll see the same output as when you write the 'Hello World!' message directly inside the <code>console.log()</code> function. How can this be?</p>
<p>This is because the message written in the code above is a <em>variable</em>.</p>
<p>In programming, a variable is simply a name that you give to a value so that you can access that value later. You can think of a variable as a label that can be tagged to a certain value, so you can refer to the value using the label.</p>
<p>To declare a variable, you need to type the keyword <code>let</code> followed by the variable name.</p>
<p>The first line in the code tells JavaScript to associate the <code>message</code> variable with the value <code>Hello World!</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello World!"</span>
</code></pre>
<p>In the second line, JavaScript is instructed to print the value of <code>message</code>, and that's exactly what it does.</p>
<p>You can change the value of your variable by re-assigning another value as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js">message <span class="token operator">=</span> <span class="token string">"Hello World!"</span>
<span class="token function">print</span><span class="token punctuation">(</span>message<span class="token punctuation">)</span>
message <span class="token operator">=</span> <span class="token string">"Nice weather!"</span>
<span class="token function">print</span><span class="token punctuation">(</span>message<span class="token punctuation">)</span>
</code></pre>
<p>Run the file and you'll see two lines printed as the output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello World!
Nice weather!
</code></pre>
<p>Variables are used to reference data so that you can use the same data multiple times in your program.</p>
<p>Next, let's see some rules for naming variables in JavaScript.</p>
<h3 id="variablenaming">Variable naming</h3>
<p>JavaScript has a few naming rules that you need to know to avoid naming errors.</p>
<p>Variable names can only contain alphabet letters, numbers, and underscores (<code>_</code>). This means you can name your variable <code>message</code>, <code>message_1</code>, <code>message_2</code>.</p>
<p>The first character of the variable name must not be a number. <code>message_1</code> is okay. <code>1_message</code> is not.</p>
<p>You can't use reserved keywords such as <code>console</code> because they are used by JavaScript to do certain things. There are many other keywords used by JavaScript that you'll learn in the following sections such as <code>if</code>, <code>for</code>, and <code>while</code>.</p>
<p>Variable names are case-sensitive, which means <code>Message</code>, <code>MESSAGE</code>, and <code>message</code> can be used to create three different variables. But of course, I don't recommend using similar names as it causes confusion.</p>
<p>Sometimes, you need more than one word to declare a variable name. JavaScript has two naming conventions that are used worldwide:</p>
<ol>
<li><code>camelCase</code></li>
<li><code>snake_case</code></li>
</ol>
<p>Camel case is a naming convention that uses an uppercase letter for the first character for subsequent words. Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myAwesomeVariable
</code></pre>
<p>The snake case naming convention uses an underscore to separate words. Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> my_awesome_variable
</code></pre>
<p>Both are acceptable naming conventions, but you should stick to one of them in your code to avoid confusion.</p>
<h3 id="constantvariable">Constant variable</h3>
<p>There are times when you need to store a value that never changes in a variable.</p>
<p>A constant variable is a variable that doesn't change its value as long as the program is running. In other programming languages, changing the value of a constant will produce an error.</p>
<p>In JavaScript, a constant variable is declared using the <code>const</code> keyword.</p>
<p>The following shows how to declare 2 constants in JavaScript:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token constant">FILE_SIZE_LIMIT</span> <span class="token operator">=</span> <span class="token number">2000</span>
<span class="token keyword">const</span> <span class="token constant">MAX_SPEED</span> <span class="token operator">=</span> <span class="token number">300</span>
</code></pre>
<p>The naming convention for a constant is to use all uppercase letters, although using lowercase letters also works. The uppercase is just a standard to make constants stand out more.</p>
<h3 id="thevarkeyword">The var keyword</h3>
<p>The <code>var</code> keyword is used to declare variables with a global scope. This keyword was the only keyword you can use to declare variables before JavaScript released the new <code>let</code> and <code>const</code> keyword in 2015.</p>
<p>As of today, you should avoid using <code>var</code> if you can, since <code>var</code> can introduce bugs that you can avoid by using the <code>let</code> keyword.</p>
<p>To show you what I mean, consider the following example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">if</span><span class="token punctuation">(</span><span class="token boolean">true</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">var</span> name <span class="token operator">=</span> <span class="token string">"Nathan"</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>name<span class="token punctuation">)</span>
</code></pre>
<p>The code above will print the <code>name</code> variable just fine, but it really should not because the variable <code>name</code> is declared inside the <code>if</code> block.</p>
<p>This is because any variable declared using the <code>var</code> keyword is accessible from everywhere. The scope of that variable is global.</p>
<p>On the other hand, the <code>let</code> keyword has a block scope, which means the variable is only accessible from the block and all its child blocks.</p>
<p>But why bother with scoping the variable? This is because when you have hundreds or thousands of code lines, it can become frustrating to trace an error that occurs because of global variables.</p>
<p>There's a principle in software development called "principles of least exposure", which means you don't expose any part of your program that's unnecessary.</p>
<p>Block scoping a variable ensures that a variable is exposed and accessible only in parts of your codebase that require the variable.</p>
<p>A variable declared using the <code>let</code> keyword is identical to a variable declared using <code>var</code> except for the scope level.</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">if</span><span class="token punctuation">(</span><span class="token boolean">true</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">let</span> name <span class="token operator">=</span> <span class="token string">"Nathan"</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>name<span class="token punctuation">)</span>  <span class="token comment">// Error: name is not defined</span>
</code></pre>
<p>This also means that you now have <code>var</code>, <code>let</code>, and <code>const</code> keywords to declare a variable. Which one to use?</p>
<p>In general, you can declare a variable with <code>const</code> first. When you code your application and realize that you need to change the variable assignment, you can change the declaration to <code>let</code>.</p>
<p>If you know from the start that the variable's value will change, then you can use <code>let</code> immediately. Just don't use <code>var</code> today or people might get mad at you.</p>
<h3 id="exercise2">Exercise #2</h3>
<p>Write a program with three variables, each with the following value:</p>
<ol>
<li>The first variable contains your name</li>
<li>The second variable contains your age</li>
<li>The third variable contains your occupation</li>
</ol>
<p>Then print the variables using the <code>console.log()</code> method. Here's the example output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">John Doe
Student
19
</code></pre>
<h3 id="summary">Summary</h3>
<p>How you use variables to make a program that does what you want it to do is one of the most important skills you can have as a programmer.</p>
<p>But before you learn more about how to make use of variables, let's learn about data types in JavaScript.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="7javascriptbasicdatatypes">7 - JavaScript Basic Data Types</h2>
<p>Data Types are simply definitions for different types of data known to a programming language.</p>
<p>A data type contains specifications about what you can and can't do with that data.</p>
<p>To show you a brain-friendly example, I'm sure you agree that <code>2 + 2 = 4</code>?</p>
<p>Well, JavaScript also agrees with that:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span> <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: 4</span>
</code></pre>
<p>But what if you try to add a number with letters as shown below?</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span> <span class="token operator">+</span> <span class="token string">"ABC"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">2ABC
</code></pre>
<p>Adding a number and letters together will cause JavaScript to concatenate or join the values together.</p>
<p>In this section, you're going to learn basic data types that JavaScript knows:</p>
<ul>
<li>Strings</li>
<li>Numbers</li>
<li>Booleans</li>
<li>Null</li>
<li>Undefined</li>
</ul>
<p>You will also see how these different types react to operators such as <code>+</code> shown in the above example.</p>
<p>First, let's start with strings.</p>
<h3 id="stringsinjavascript">Strings in JavaScript</h3>
<p>Strings are simply data defined as a series of characters.</p>
<p>You've seen an example of string data previously when you call the <code>console.log()</code> function to print a message:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello, Sunshine!"</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>message<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello, Sunshine!</span>
</code></pre>
<p>A string needs to be enclosed in quotations. You can use double quotes or single quotes, but they have to match.</p>
<p>You'll get an error when you use different quotation marks like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// Invalid or unexpected token</span>
<span class="token keyword">let</span> message <span class="token operator">=</span> "Hello'<span class="token punctuation">;</span> 
</code></pre>
<p>You can join two or more strings as one with the plus <code>+</code> symbol. Don't forget to add a space before the next string or you'll get a string without spaces!</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello "</span> <span class="token operator">+</span> <span class="token string">"and "</span> <span class="token operator">+</span> <span class="token string">"Goodbye!"</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>message<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: Hello and Goodbye!</span>
</code></pre>
<p>When printing a variable's value, you can also add strings in the <code>console.log()</code> function directly as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello, Dave!"</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The message is: "</span> <span class="token operator">+</span> message<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: The message is: Hello, Dave!</span>
</code></pre>
<p>This is particularly useful when you have multiple strings to console.log in one sentence as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> name <span class="token operator">=</span> <span class="token string">"John"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> topic <span class="token operator">=</span> <span class="token string">"JavaScript"</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>name <span class="token operator">+</span> <span class="token string">" is learning "</span> <span class="token operator">+</span> topic <span class="token operator">+</span> <span class="token string">" today"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: John is learning JavaScript today</span>
</code></pre>
<p>Or you can also use the template strings format, which allows you to embed a variable directly inside the string as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> name <span class="token operator">=</span> <span class="token string">"John"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> topic <span class="token operator">=</span> <span class="token string">"JavaScript"</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> is learning </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>topic<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> today</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: John is learning JavaScript today</span>
</code></pre>
<p>To use the template strings format, you need to use the backtick <code>(`)</code> character to wrap the string instead of quotations.</p>
<p>The variable is embedded in the string using the dollar symbol and curly brackets as in <code>${variable}</code>.</p>
<p>This way, JavaScript knows that you're referencing a variable inside the string.</p>
<p>When you have multiple strings to print in a single line, then the template strings format is more convenient because you didn't have to break the string with quotations and concatenations.</p>
<p>Next, strings can also represent numbers. You surround the numbers in quotations as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> score <span class="token operator">=</span> <span class="token string">"10"</span> <span class="token operator">+</span> <span class="token string">"30"</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>score<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: 1030</span>
</code></pre>
<p>When you join two string numbers with a <code>+</code> symbol, JavaScript will join the two numbers instead of performing arithmetic addition.</p>
<p>This is how strings work in JavaScript. Let's look at numbers next.</p>
<h3 id="numbersintegersandfloatsinjavascript">Numbers (integers and floats) in JavaScript</h3>
<p>Number data types represent different kinds of numbers. There are two types of numbers in JavaScript:</p>
<ul>
<li>Integers</li>
<li>Floats</li>
</ul>
<p>An integer is a whole number without decimals and fractions. Below, you see examples of two integers <code>x</code> and <code>y</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> y <span class="token operator">=</span> <span class="token number">2</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x <span class="token operator">+</span> y<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: 3</span>
</code></pre>
<p>On the other hand, floats refer to numbers with decimal points like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> f <span class="token operator">=</span> <span class="token number">1.2</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> z <span class="token operator">=</span> <span class="token number">2.35</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>f <span class="token operator">+</span> z<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// Output: 3.55</span>
</code></pre>
<p>To create a float, you need to write a number and use <code>.</code> to define the decimal values.</p>
<p>With number types, you can perform arithmetic operations such as addition <code>+</code>, subtraction <code>-</code>, division <code>/</code>, and multiplication <code>*</code> just like how you use a calculator.</p>
<h3 id="booleansinjavascript">Booleans in JavaScript</h3>
<p>Boolean is a type that represents <code>true</code> and <code>false</code> values.</p>
<p>You can think of Booleans as a light switch that can only be in one of two positions: on or off.</p>
<p>So it is with Boolean values in programming languages. They are used when JavaScript needs to make a decision: Go left or go right? Right or wrong?</p>
<p>Here's how you create Boolean values in JavaScript:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> on <span class="token operator">=</span> <span class="token boolean">true</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> off <span class="token operator">=</span> <span class="token boolean">false</span><span class="token punctuation">;</span>
</code></pre>
<p>This data type is frequently used when you need to make a decision using a control flow. You'll see why Boolean values are very useful in developing a program later in Section 9.</p>
<h3 id="undefinedinjavascript">Undefined in JavaScript</h3>
<p>Undefined is a data type in JavaScript used to represent a variable that hasn't been assigned any value yet.</p>
<p>Anytime you declared a variable without assigning any value, the <code>undefined</code> value will be assigned to that variable. For example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> first_name<span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>first_name<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// undefined</span>
</code></pre>
<p>You can also assign <code>undefined</code> to a variable explicitly as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> last_name <span class="token operator">=</span> <span class="token keyword">undefined</span><span class="token punctuation">;</span>
</code></pre>
<p>But this is usually not recommended, because JavaScript has another value called <code>null</code> which is used to mark a variable as empty.</p>
<h3 id="nullinjavascript">Null in JavaScript</h3>
<p>The <code>null</code> value is a special data type that represents an empty or unknown value. Here's how you assign a variable as null:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> first_name <span class="token operator">=</span> <span class="token keyword">null</span><span class="token punctuation">;</span>
</code></pre>
<p>The code above means that the value of <code>first_name</code> is empty or unknown.</p>
<p>At this point, you may be thinking what's the difference between <code>undefined</code> and <code>null</code>? They seem to serve a similar purpose.</p>
<p>And you are correct. Both <code>undefined</code> and <code>null</code> are values that represent nothing, and other programming languages usually only have one, and that is <code>null</code>.</p>
<p>In JavaScript, the <code>undefined</code> value is reserved as the default value when a variable is declared, while <code>null</code> means you intentionally assign an "empty" value for the variable.</p>
<p>This slight difference will come to play later when you learn about functions in Section 11.</p>
<p>For now, just keep in mind that JavaScript treats <code>undefined</code> as the "default" empty value and <code>null</code> as the "intentional" empty value.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="8typeconversionandcoercion">8 - Type Conversion and Coercion</h2>
<p>At times, you might want to convert one data type into another so that the program runs as expected.</p>
<p>For example, suppose you need to convert a string into an integer so you can perform an addition between numbers.</p>
<p>If you have one of the numbers as a string, JavaScript joins them together instead of adding:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token string">"7"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> y <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x <span class="token operator">+</span> y<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 75</span>
</code></pre>
<p>To add the two numbers properly, you need to convert the <code>x</code> variable into an integer.</p>
<p>Changing the data from one type to another is also known as type conversion or type casting. There are 3 functions frequently used to do type conversion:</p>
<ul>
<li><code>Number()</code></li>
<li><code>String()</code></li>
<li><code>Boolean()</code></li>
</ul>
<p>As their name implies, these type conversion functions will attempt to convert any value you specified inside the parentheses to the type of the same name.</p>
<p>To convert a string into an integer, you can use the <code>int()</code> function:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token string">"7"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> y <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span>

<span class="token comment">// Convert x to integer</span>
x <span class="token operator">=</span> <span class="token function">Number</span><span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x <span class="token operator">+</span> y<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 12</span>
</code></pre>
<p>On the other hand, the <code>String()</code> function converts a value of another type to a string. If you type <code>String(true)</code>, then you'll get 'true' back.</p>
<p>Passing a value of the same type as the function has no effect. It will just return the same value back.</p>
<h3 id="typecoercion">Type coercion</h3>
<p>In JavaScript, type coercion is a process where a value of one type is implicitly converted into another type.</p>
<p>This is automatically done by JavaScript so that your code won't cause an error. But as you'll see in this section, type coercion can actually cause undesired behavior in the program.</p>
<p>Let's consider what happens when you perform an addition between a <code>number</code> and a <code>string</code> in JavaScript:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">1</span> <span class="token operator">+</span> <span class="token string">"1"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>As you've seen in the previous section, JavaScript will consider the number as a string and join the two letters as <code>11</code> instead of adding them (<code>1 + 1 = 2</code>)</p>
<p>But you need to know that other programming languages don't respond the same way.</p>
<p>Programming languages like Ruby or Python will respond by stopping your program and giving an error as feedback. It will respond with something along the lines of "Cannot perform addition between a number and a string".</p>
<p>But JavaScript will see this and said: "I cannot do the operation you requested <strong>as it is</strong>, but I can do it if the number <code>1</code> is converted to a <code>string</code>, <strong>so I'll do just that</strong>."</p>
<p>And that's exactly what type coercion is. JavaScript notices that it doesn't know how to execute your code, but it doesn't stop the program and respond with an error.</p>
<p>Instead, it will change the data type of one of the values without telling you.</p>
<p>While type coercion doesn't cause any errors, the output is actually something you don't want either.</p>
<h3 id="typecoercionrules">Type coercion rules</h3>
<p>Type coercion rules are never stated clearly anywhere, but I did find some rules by trying various silly code myself.</p>
<p>It seems that JavaScript will first convert data types to <code>string</code> when it finds different data types:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token number">1</span> <span class="token operator">+</span> <span class="token string">"1"</span> <span class="token comment">// "11"</span>
<span class="token punctuation">[</span><span class="token number">1</span> <span class="token punctuation">,</span><span class="token number">2</span><span class="token punctuation">]</span> <span class="token operator">+</span> <span class="token string">"1"</span> <span class="token comment">// "1,21"</span>
<span class="token boolean">true</span> <span class="token operator">+</span> <span class="token string">"1"</span> <span class="token comment">// "true1"</span>
</code></pre>
<p>But the order of the values matters when you have an object. Writing objects first always returns numeric <code>1</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token punctuation">{</span> <span class="token literal-property property">a</span><span class="token operator">:</span> <span class="token number">1</span> <span class="token punctuation">}</span> <span class="token operator">+</span> <span class="token string">"1"</span> <span class="token comment">// 1</span>
<span class="token string">"1"</span> <span class="token operator">+</span> <span class="token punctuation">{</span> <span class="token literal-property property">a</span><span class="token operator">:</span> <span class="token number">1</span> <span class="token punctuation">}</span> <span class="token comment">// "1[object Object]"</span>
<span class="token boolean">true</span> <span class="token operator">+</span> <span class="token punctuation">{</span> <span class="token literal-property property">a</span><span class="token operator">:</span> <span class="token number">1</span> <span class="token punctuation">}</span> <span class="token comment">// "true[object Object]"</span>
<span class="token punctuation">{</span> <span class="token literal-property property">a</span><span class="token operator">:</span> <span class="token number">1</span> <span class="token punctuation">}</span> <span class="token operator">+</span> <span class="token number">1</span> <span class="token comment">// 1</span>
</code></pre>
<p>JavaScript can calculate between boolean and numeric types, because boolean values <code>true</code> and <code>false</code> implicitly has the numeric value of <code>1</code> and <code>0</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token boolean">true</span> <span class="token operator">+</span> <span class="token number">1</span> <span class="token comment">// 1+1 = 1</span>
<span class="token boolean">false</span> <span class="token operator">+</span> <span class="token number">1</span> <span class="token comment">// 0+1 = 1</span>
<span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span><span class="token number">2</span><span class="token punctuation">]</span> <span class="token operator">+</span> <span class="token number">1</span> <span class="token comment">// "1,21"</span>
</code></pre>
<p>Type coercion is always performed <strong>implicitly</strong>. When you assign the value as a variable, the variable type will never change outside of the operation:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myNumber <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myNumber <span class="token operator">+</span> <span class="token string">"1"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// prints 11</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myNumber<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// still prints number 1 and not string</span>
</code></pre>
<p>You can try to find some more on your own, but you hopefully understand what type coercion is and how it works by now.</p>
<h3 id="whyyoushouldavoidtypecoercion">Why you should avoid type coercion</h3>
<p>JavaScript developers are generally divided into two camps when talking about type coercion:</p>
<ul>
<li>Those who think it's a feature</li>
<li>Those who think it's a bug</li>
</ul>
<p>If you ask me, I would recommend that you avoid using type coercion in your code all the time.</p>
<p>The reason is that I've never found a problem where type coercion is required for the solution, and when I need to convert one type into another, it's always better to do so explicitly:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> price <span class="token operator">=</span> <span class="token string">"50"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> tax <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span>

<span class="token keyword">let</span> totalPrice <span class="token operator">=</span> <span class="token function">Number</span><span class="token punctuation">(</span>price<span class="token punctuation">)</span> <span class="token operator">+</span> <span class="token function">Number</span><span class="token punctuation">(</span>tax<span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>totalPrice<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Using explicit type conversion functions such as <code>Number()</code> and <code>String()</code> will make your code clear and transparent. You don't need to guess the correct data type required in your program.</p>
<p>Type coercion is one of the unique features in JavaScript that may confuse beginners, so it's good to clear it up early.</p>
<p>Next, we'll learn about JavaScript operators.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="9operatorsinjavascript">9 - Operators in JavaScript</h2>
<p>As the name implies, operators are symbols you can use to perform operations on your data.</p>
<p>You've seen some examples of using the plus <code>+</code> operator to join multiple strings and add two numbers together. Of course, JavaScript has more than one operator as you'll discover in this section.</p>
<p>Since you've learned about data types and conversion previously, learning operators should be relatively easy.</p>
<h3 id="arithmeticoperators">Arithmetic operators</h3>
<p>The arithmetic operators are used to perform mathematical operations like additions and subtractions.</p>
<p>These operators are frequently used with number data types. Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">10</span> <span class="token operator">-</span> <span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 7</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span> <span class="token operator">+</span> <span class="token number">4</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 6</span>
</code></pre>
<p>In total, there are 8 arithmetic operators in JavaScript:</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Operation example</th>
<th>Meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td>Addition</td>
<td><code>x + y</code></td>
<td>Returns the sum between the two operands</td>
</tr>
<tr>
<td>Subtraction</td>
<td><code>x - y</code></td>
<td>Returns the difference between the two operands</td>
</tr>
<tr>
<td>Multiplication</td>
<td><code>x * y</code></td>
<td>Returns the multiplication between the two operands</td>
</tr>
<tr>
<td>Exponentiation</td>
<td><code>x ** y</code></td>
<td>Returns the value of the left operand raised to the power of the right operand</td>
</tr>
<tr>
<td>Division</td>
<td><code>x / y</code></td>
<td>Returns the value of the left operand divided by the right operand</td>
</tr>
<tr>
<td>Remainder</td>
<td><code>x % y </code></td>
<td>Returns the remainder of the left operand after being divided by the right operand</td>
</tr>
<tr>
<td>Increment</td>
<td><code>x++</code></td>
<td>Returns the operand plus one</td>
</tr>
<tr>
<td>Decrement</td>
<td><code>x--</code></td>
<td>Returns the operand minus one</td>
</tr>
</tbody>
</table>
<p>These operators are pretty straightforward, so you can try them on your own.</p>
<p>As you've seen in the previous section, the <code>+</code> operator can also be used on strings data to merge multiple strings as one:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello "</span> <span class="token operator">+</span> <span class="token string">"human!"</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>message<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello human!</span>
</code></pre>
<p>When you add a number and a string, JavaScript will perform a type coercion and treats the number value as a string value:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> sum <span class="token operator">=</span> <span class="token string">"Hi "</span> <span class="token operator">+</span> <span class="token number">89</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>sum<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hi 89</span>
</code></pre>
<p>Using any other arithmetic operator with strings will cause JavaScript to return a <code>NaN</code> value.</p>
<h3 id="theassignmentoperator">The assignment operator</h3>
<p>The next operator to learn is the assignment operator, which is represented by the equals <code>=</code> sign.</p>
<p>In JavaScript, the assignment operator is used to assign data or a value to a variable.</p>
<p>You've seen some examples of using the assignment operator before, so here's a reminder:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// Assign the string value 'Hello' to the 'message' variable</span>
<span class="token keyword">let</span> message <span class="token operator">=</span> <span class="token string">"Hello"</span><span class="token punctuation">;</span>

<span class="token comment">// Assign the Boolean value true to the 'on' variable</span>
<span class="token keyword">let</span> on <span class="token operator">=</span> <span class="token boolean">true</span><span class="token punctuation">;</span>
</code></pre>
<p>You may've noticed that the equals sign has a slightly different meaning in programming than in math, and you're correct!</p>
<p>The assignment operator isn't used to compare if a number equals another number in programming.</p>
<p>If you want to do that kind of comparison, then you need to use the equal to <code>==</code> operator.</p>
<p>Assignment operators can also be combined with arithmetic operators, so that you can add or subtract values from the left operand.</p>
<p>See the table below for the types of assignment operators:</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Operation example</th>
<th>Meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td>Assignment</td>
<td><code>x = y</code></td>
<td><code>x = y</code></td>
</tr>
<tr>
<td>Addition assignment</td>
<td><code>x += y</code></td>
<td><code>x = x + y</code></td>
</tr>
<tr>
<td>Subtraction assignment</td>
<td><code>x -= y</code></td>
<td><code>x = x - y</code></td>
</tr>
<tr>
<td>Multiplication assignment</td>
<td><code>x *= y</code></td>
<td><code>x = x * y</code></td>
</tr>
<tr>
<td>Division assignment</td>
<td><code>x /= y </code></td>
<td><code>x = x / y</code></td>
</tr>
<tr>
<td>Remainder assignment</td>
<td><code>x %= y</code></td>
<td><code>x = x % y</code></td>
</tr>
</tbody>
</table>
<p>Next, let's look at comparison operators.</p>
<h3 id="thecomparisonoperators">The comparison operators</h3>
<p>Comparison operators are used to compare two values. The operators in this category will return Boolean values: either <code>true</code> or <code>false</code>.</p>
<p>The following table shows all comparison operators available in JavaScript:</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Operation example</th>
<th>Meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td>Equal</td>
<td><code>x == y</code></td>
<td>Returns <code>true</code> if the operands are equal</td>
</tr>
<tr>
<td>Not equal</td>
<td><code>x != y</code></td>
<td>Returns <code>true</code> if the operands are not equal</td>
</tr>
<tr>
<td>Strict equal</td>
<td><code>x === y</code></td>
<td>Returns <code>true</code> if the operands are equal and have the same type</td>
</tr>
<tr>
<td>Strict not equal</td>
<td><code>x !== y</code></td>
<td>Returns <code>true</code> if the operands are not equal, or have different types</td>
</tr>
<tr>
<td>Greater than</td>
<td><code>x &gt; y</code></td>
<td>Returns <code>true</code> if the left operand is greater than the right operand</td>
</tr>
<tr>
<td>Greater than or equal</td>
<td><code>x &gt;= y</code></td>
<td>Returns <code>true</code> if the left operand is greater than or equal to the right operand</td>
</tr>
<tr>
<td>Less than</td>
<td><code>x &lt; y </code></td>
<td>Returns <code>true</code> if the left operand is less than the right operand</td>
</tr>
<tr>
<td>Less than or equal</td>
<td><code>x &lt;= y</code></td>
<td>Returns <code>true</code> if the left operand is less than or equal to the right operand</td>
</tr>
</tbody>
</table>
<p>Here are some examples of using these operators:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">9</span> <span class="token operator">==</span> <span class="token number">9</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">9</span> <span class="token operator">!=</span> <span class="token number">20</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span> <span class="token operator">&gt;</span> <span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span> <span class="token operator">&lt;</span> <span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">5</span> <span class="token operator">&gt;=</span> <span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">10</span> <span class="token operator">&lt;=</span> <span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>
</code></pre>
<p>The comparison operators can also be used to compare strings like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"ABC"</span> <span class="token operator">==</span> <span class="token string">"ABC"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"ABC"</span> <span class="token operator">==</span> <span class="token string">"abc"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Z"</span> <span class="token operator">==</span> <span class="token string">"A"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>
</code></pre>
<p>String comparisons are case-sensitive, as shown in the example above.</p>
<p>JavaScript also has two versions of each comparison operator: loose and strict.</p>
<p>In strict mode, JavaScript will compare the types without performing a type coercion.</p>
<p>You need to add one more equal <code>=</code> symbol to the operator as follows</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"9"</span> <span class="token operator">==</span> <span class="token number">9</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"9"</span> <span class="token operator">===</span> <span class="token number">9</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token boolean">true</span> <span class="token operator">==</span> <span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token boolean">true</span> <span class="token operator">===</span> <span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>
</code></pre>
<p>You should use the strict comparison operators unless you have a specific reason not to.</p>
<h3 id="logicaloperators">Logical operators</h3>
<p>The logical operators are used to check whether one or more expressions result in either <code>True</code> or <code>False</code>.</p>
<p>There are three logical operators that JavaScript has:</p>
<table>
<thead>
<tr>
<th>Name</th>
<th>Operation example</th>
<th>Meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td>Logical AND</td>
<td><code>x &amp;&amp; y</code></td>
<td>Returns <code>true</code> if all operands are <code>true</code>, else returns <code>false</code></td>
</tr>
<tr>
<td>Logical OR</td>
<td><code>x || y</code></td>
<td>Returns <code>true</code> if one of the operands is <code>true</code>, else returns <code>false</code></td>
</tr>
<tr>
<td>Logical NOT</td>
<td><code>!x</code></td>
<td>Reverse the result: returns <code>true</code> if <code>false</code> and vice versa</td>
</tr>
</tbody>
</table>
<p>These operators can only return Boolean values. For example, you can determine whether '7 is greater than 2' and '5 is greater than 4':</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">7</span> <span class="token operator">&gt;</span> <span class="token number">2</span> <span class="token operator">&amp;&amp;</span> <span class="token number">5</span> <span class="token operator">&gt;</span> <span class="token number">4</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>
</code></pre>
<p>These logical operators follow the laws of mathematical logic:</p>
<ol>
<li><code>&amp;&amp;</code> AND operator - if any expression returns <code>false</code>, the result is <code>false</code></li>
<li><code>||</code> OR operator - if any expression returns <code>true</code>, the result is <code>true</code></li>
<li><code>!</code> NOT operator - negates the expression, returning the opposite.</li>
</ol>
<p>Let's have a little exercise. Try to run these statements on your computer. Can you guess the results?</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token boolean">true</span> <span class="token operator">&amp;&amp;</span> <span class="token boolean">false</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token boolean">false</span> <span class="token operator">||</span> <span class="token boolean">false</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token operator">!</span><span class="token boolean">true</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>These logical operators will come in handy when you need to assert that a specific requirement is fulfilled in your code.</p>
<h3 id="thetypeofoperator">The <code>typeof</code> operator</h3>
<p>JavaScript allows you to check the data type by using the <code>typeof</code> operator. To use the operator, you need to call it before specifying the data:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token keyword">typeof</span> x<span class="token punctuation">)</span> <span class="token comment">//  'number'</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token keyword">typeof</span> <span class="token string">"Nathan"</span><span class="token punctuation">)</span> <span class="token comment">// 'string'</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token keyword">typeof</span> <span class="token boolean">true</span><span class="token punctuation">)</span> <span class="token comment">// 'boolean'</span>
</code></pre>
<p>The <code>typeof</code> operator returns the type of the data as a string. The 'number' type represents both integer and float types, the string and boolean represent their respective types.</p>
<h3 id="exercise3">Exercise #3</h3>
<p>Guess the result of these operators in action:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">19</span> <span class="token operator">%</span> <span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">10</span> <span class="token operator">==</span> <span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">10</span> <span class="token operator">!==</span> <span class="token string">"10"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span> <span class="token operator">&lt;</span> <span class="token string">"10"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"5"</span> <span class="token operator">&gt;</span> <span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token punctuation">(</span><span class="token boolean">false</span> <span class="token operator">&amp;&amp;</span> <span class="token boolean">true</span><span class="token punctuation">)</span> <span class="token operator">||</span> <span class="token boolean">false</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="10javascriptarrays">10 - JavaScript Arrays</h2>
<p>An array is an object data type that can be used to hold more than one value. An array can be a list of strings, numbers, booleans, objects, or a mix of them all.</p>
<p>To create an array, you need to use the square brackets <code>[]</code> and separate the items using a comma.</p>
<p>Here's how to create a list of strings:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> birds <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Owl'</span><span class="token punctuation">,</span> <span class="token string">'Eagle'</span><span class="token punctuation">,</span> <span class="token string">'Parrot'</span><span class="token punctuation">,</span> <span class="token string">'Falcon'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
</code></pre>
<p>You can think of an array as a list of items, each stored in a locker compartment:</p>
<p><img src="https://www.freecodecamp.org/news/content/images/2023/07/10-array-as-a-locker-1.png" alt="Array as a locker illustration" loading="lazy" width="1920" height="1330"></p>
<p>You can also declare an empty array without any value:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> birds <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
</code></pre>
<p>An array can also have a mix of values like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> mixedArray <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Bird'</span><span class="token punctuation">,</span> <span class="token boolean">true</span><span class="token punctuation">,</span> <span class="token number">10</span><span class="token punctuation">,</span> <span class="token number">5.17</span><span class="token punctuation">]</span>
</code></pre>
<p>The array above contains a string, a boolean, an integer, and a float.</p>
<h3 id="arrayindexposition">Array index position</h3>
<p>JavaScript remembers the position of the elements within an array. The position of an element is also called an index number.</p>
<p>Going back to the locker example, you can think of index numbers as the locker numbers. The index number starts from <code>0</code> as follows:</p>
<p><img src="https://www.freecodecamp.org/news/content/images/2023/07/10-array-index-analogy.png" alt="Array index numbers as locker numbers" loading="lazy" width="1920" height="1330"></p>
<p>To access or change the value of an array, you need to add the square brackets notation <code>[x]</code> next to the array name, where <code>x</code> is the index number of that element. Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// Access the first element in the array</span>
myArray<span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

<span class="token comment">// Access the second element in the array</span>
myArray<span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
</code></pre>
<p>Suppose you want to print the string 'Owl' from the <code>birds</code> array. Here's how you can do it.</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> birds <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Owl'</span><span class="token punctuation">,</span> <span class="token string">'Eagle'</span><span class="token punctuation">,</span> <span class="token string">'Parrot'</span><span class="token punctuation">,</span> <span class="token string">'Falcon'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>birds<span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Owl</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>birds<span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Eagle</span>
</code></pre>
<p>There you go. You need to type the name of the array, followed by the index number wrapped in square brackets.</p>
<p>You can also assign a new value to a specific index using the assignment operator.</p>
<p>Let's replace 'Parrot' with 'Vulture':</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> birds <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Owl'</span><span class="token punctuation">,</span> <span class="token string">'Eagle'</span><span class="token punctuation">,</span> <span class="token string">'Parrot'</span><span class="token punctuation">,</span> <span class="token string">'Falcon'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
birds<span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">]</span> <span class="token operator">=</span> <span class="token string">'Vulture'</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>birds<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// ['Owl', 'Eagle', 'Vulture', 'Falcon']</span>
</code></pre>
<p>Because the array index starts from zero, the value 'Parrot' is stored at index 2 and not 3.</p>
<h3 id="specialmethodsforarraymanipulation">Special methods for array manipulation</h3>
<p>Since array is an object, you can call methods that are provided by JavaScript to manipulate the array values.</p>
<p>For example, you can use the <code>push()</code> method to add an item to the end of the array:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> birds <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Owl'</span><span class="token punctuation">,</span> <span class="token string">'Eagle'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

birds<span class="token punctuation">.</span><span class="token function">push</span><span class="token punctuation">(</span><span class="token string">'Sparrow'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>birds<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// ['Owl', 'Eagle', 'Sparrow']</span>
</code></pre>
<p>Another method called <code>pop()</code> can be used to remove an item from the end of an array:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> birds <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Owl'</span><span class="token punctuation">,</span> <span class="token string">'Eagle'</span><span class="token punctuation">,</span> <span class="token string">'Sparrow'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

birds<span class="token punctuation">.</span><span class="token function">pop</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>birds<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// ['Owl', 'Eagle']</span>
</code></pre>
<p>The <code>unshift()</code> method can be used to add an item from the front at index 0:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> fishes <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Salmon'</span><span class="token punctuation">,</span> <span class="token string">'Goldfish'</span><span class="token punctuation">,</span> <span class="token string">'Tuna'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

fishes<span class="token punctuation">.</span><span class="token function">unshift</span><span class="token punctuation">(</span><span class="token string">'Sardine'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>fishes<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// ['Sardine', 'Salmon', 'Goldfish', 'Tuna']</span>
</code></pre>
<p>On the other hand, the <code>shift()</code> method can be used to remove an item from index 0:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> fishes <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Salmon'</span><span class="token punctuation">,</span> <span class="token string">'Goldfish'</span><span class="token punctuation">,</span> <span class="token string">'Tuna'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

fishes<span class="token punctuation">.</span><span class="token function">shift</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>fishes<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// ['Goldfish', 'Tuna']</span>
</code></pre>
<p>The <code>indexOf()</code> method can be used to find and return the index of an item in the array.</p>
<p>The method will return <code>-1</code> when the item isn't found inside the array:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> fishes <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Salmon'</span><span class="token punctuation">,</span> <span class="token string">'Goldfish'</span><span class="token punctuation">,</span> <span class="token string">'Tuna'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

<span class="token keyword">let</span> pos <span class="token operator">=</span> fishes<span class="token punctuation">.</span><span class="token function">indexOf</span><span class="token punctuation">(</span><span class="token string">'Tuna'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>pos<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 2</span>
</code></pre>
<p>To get the size of an array, you can access the <code>length</code> property:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> fishes <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">'Salmon'</span><span class="token punctuation">,</span> <span class="token string">'Goldfish'</span><span class="token punctuation">,</span> <span class="token string">'Tuna'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>fishes<span class="token punctuation">.</span>length<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 3</span>
</code></pre>
<p>Note that we don't add parentheses next to the <code>length</code> keyword above. This is because <code>length</code> is a property of the array object and not a method.</p>
<p>We'll learn more about objects in the coming tutorials.</p>
<h3 id="exercise4">Exercise #4</h3>
<p>Create an array named <code>colors</code> that include the 'red', 'green, and 'blue' colors.</p>
<p>First, add a 'black' color after the last index of the array. Then print the array.</p>
<p>Next, remove the value 'red' and swap the position of 'green' and 'blue'. Print the array.</p>
<p>Finally, add the color 'yellow' on the first index of the array, then print the array.</p>
<p>The result output is as follows:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">[ 'red', 'green', 'blue', 'black' ]
[ 'blue', 'green', 'black' ]
[ 'yellow', 'blue', 'green', 'black' ]
</code></pre>
<p>You need to modify the original array using the methods explained in this section.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="11controlflowsconditionalsinjavascript">11 - Control Flows (Conditionals) in JavaScript</h2>
<p>Up until now, the JavaScript code you've written is executed line by line from top to bottom. But what if you want to run some lines of code only when a certain condition is met?</p>
<p>A computer program usually needs to take into account many different conditions that can arise during the program's execution.</p>
<p>This is similar to how a human makes decisions in their life. For example, do you have money to cover the vacation to Japan? If yes, go. If not, then save more money!</p>
<p>This is where control flow comes in. <strong>Control flow</strong> is a feature in a programming language that allows you to selectively run specific code based on the different conditions that may arise.</p>
<p>Using control flows allows you to define multiple paths a program can take based on the conditions present in your program.</p>
<p>There are two types of control flows commonly used in JavaScript: conditionals and loops.</p>
<p>This section will focus on the conditional statements such as:</p>
<ol>
<li><code>if...else</code> statement</li>
<li><code>switch...case</code> statement</li>
</ol>
<p>You'll learn about loop statements in the next section.</p>
<h3 id="theifelsestatement">The if...else statement</h3>
<p>The <code>if</code> statement allows you to create a program that runs only if a specific condition is met.</p>
<p>The syntax for the <code>if</code> statement is as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">if</span> <span class="token punctuation">(</span>condition<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token comment">// code to execute if condition is true</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Let's see an example. Suppose you want to go on a vacation that requires 5000 dollars.</p>
<p>Using the <code>if</code> statement, here's how you check if you have enough balance:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> balance <span class="token operator">=</span> <span class="token number">7000</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>balance <span class="token operator">&gt;</span> <span class="token number">5000</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You have the money for this trip. Let's go!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Run the code above once, and you'll see the string printed on the terminal.</p>
<p>Now change the value of <code>balance</code> to <code>3000</code> and you'll get no response.</p>
<p>This happens because the code inside the <code>if</code> statement is only executed when the condition is <code>true</code>.</p>
<p>After the <code>if</code> statement, you can write another line of code below it as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> balance <span class="token operator">=</span> <span class="token number">7000</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>balance <span class="token operator">&gt;</span> <span class="token number">5000</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You have the money for this trip. Let's go!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The end!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>The second <code>console.log()</code> call above will be executed no matter what value you assign to the <code>balance</code> variable.</p>
<p>If you want it to execute only when the <code>if</code> condition is met, then put the line inside the curly brackets as well:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> balance <span class="token operator">=</span> <span class="token number">7000</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>balance <span class="token operator">&gt;</span> <span class="token number">5000</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You have the money for this trip. Let's go!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The end!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Next, suppose you need to run some code only when the <code>if</code> statement condition is not fulfilled.</p>
<p>This is where the <code>else</code> statement comes in. The <code>else</code> statement is used to run code only when the <code>if</code> statement is not fulfilled.</p>
<p>Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> balance <span class="token operator">=</span> <span class="token number">7000</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>balance <span class="token operator">&gt;</span> <span class="token number">5000</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You have the money for this trip. Let's go!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Sorry, not enough money. Save more!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The end!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Now change the value of <code>balance</code> to be less than <code>5000</code>, and you'll trigger the <code>else</code> block in the example.</p>
<p>JavaScript also has the <code>else if</code> statement which allows you to write another condition to check should the <code>if</code> statement condition isn't met.</p>
<p>Consider the example below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> balance <span class="token operator">=</span> <span class="token number">7000</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>balance <span class="token operator">&gt;</span> <span class="token number">5000</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You have the money for this trip. Let's go!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>balance <span class="token operator">&gt;</span> <span class="token number">3000</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You only have enough money for a staycation"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Sorry, not enough money. Save more!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The end!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>When the <code>balance</code> amount is less than <code>5000</code>, the <code>else if</code> statement will check if the <code>balance</code> is more than <code>3000</code>. If it does, then the program will proceed to recommend you do a staycation.</p>
<p>You can write as many <code>else if</code> statements as you need, and each one will be executed only if the previous statement isn't met.</p>
<p>Together, the <code>if..else..else if</code> statements allow you to execute different blocks of code depending on the condition the program faced.</p>
<h3 id="theswitchcasestatement">The switch...case statement</h3>
<p>The <code>switch</code> statement is a part of core JavaScript syntax that allows you to control the execution flow of your code.</p>
<p>It's often thought of as an alternative to the <code>if..else</code> statement that gives you more readable code, especially when you have many different conditions to assess.</p>
<p>Here's an example of a working <code>switch</code> statement. I will explain the code below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> age <span class="token operator">=</span> <span class="token number">15</span><span class="token punctuation">;</span>
<span class="token keyword">switch</span> <span class="token punctuation">(</span>age<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token number">10</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Age is 10"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">20</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Age is 20"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">default</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Age is neither 10 or 20"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>First, you need to pass an expression to be evaluated by the <code>switch</code> statement into the parentheses. In the example, the <code>age</code> variable is passed as an argument for evaluation.</p>
<p>Then, you need to write the <code>case</code> values that the <code>switch</code> statement will try to match with your expression. The <code>case</code> value is immediately followed by a colon (<code>:</code>) to mark the start of the case block:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">case</span> <span class="token string">"apple"</span><span class="token operator">:</span>
</code></pre>
<p>Keep in mind the data type of the <code>case</code> value that you want to match with the expression. If you want to match a <code>string</code>, then you need to put a <code>string</code>. <code>switch</code> statements <strong>won't perform type coercion</strong> when you have a <code>number</code> as the argument but put a <code>string</code> for the case:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">switch</span> <span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token string">"1"</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>The number expression doesn't match the string case value, so JavaScript won't log anything to the console.</p>
<p>The same also happens for boolean values. The number <code>1</code> won't be coerced as <code>true</code> and the number <code>0</code> won't be coerced as <code>false</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">switch</span> <span class="token punctuation">(</span><span class="token number">0</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token boolean">true</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello True!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token boolean">false</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Bonjour False!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">default</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"No matching case"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<h3 id="theswitchstatementbody">The switch statement body</h3>
<p>The <code>switch</code> statement body is composed of three keywords:</p>
<ul>
<li><code>case</code> keyword for starting a case block</li>
<li><code>break</code> keyword for stopping the <code>switch</code> statement from running the next <code>case</code></li>
<li><code>default</code> keyword for running a piece of code when no matching <code>case</code> is found.</li>
</ul>
<p>When your expression finds a matching <code>case</code>, JavaScript will execute the code following the <code>case</code> statement until it finds the <code>break</code> keyword. If you omit the <code>break</code> keyword, then the code execution will continue to the next block.</p>
<p>Take a look at the following example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">switch</span> <span class="token punctuation">(</span><span class="token number">0</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token number">1</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Value is one"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">0</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Value is zero"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token keyword">default</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"No matching case"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>When you execute the code above, JavaScript will print the following log:</p>
<pre class="language-shell" tabindex="0"><code class="language-shell"><span class="token operator">&gt;</span> <span class="token string">"Value is zero"</span>
<span class="token operator">&gt;</span> <span class="token string">"No matching case"</span>
</code></pre>
<p>This is because without the <code>break</code> keyword, <code>switch</code> will continue to evaluate the expression against the remaining cases even when a matching case is already found.</p>
<p>Your switch evaluation may match more than one case, so the <code>break</code> keyword is commonly used to exit the process once a match is found.</p>
<p>Finally, you can also put expressions as <code>case</code> values:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">switch</span> <span class="token punctuation">(</span><span class="token number">20</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token number">10</span> <span class="token operator">+</span> <span class="token number">10</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"value is twenty"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>But you need to keep in mind that the value for a <code>case</code> block <strong>must exactly match</strong> the <code>switch</code> argument.</p>
<p>One of the most common mistakes when using the <code>switch</code> statement is that people think <code>case</code> value gets evaluated as <code>true</code> or <code>false</code>.</p>
<p>The following <code>case</code> blocks won't work in <code>switch</code> statements:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> age <span class="token operator">=</span> <span class="token number">5</span><span class="token punctuation">;</span>

<span class="token keyword">switch</span> <span class="token punctuation">(</span>age<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> age <span class="token operator">&lt;</span> <span class="token number">10</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Value is less than ten"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> age <span class="token operator">&lt;</span> <span class="token number">20</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Value is less than twenty"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">default</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Value is twenty or more"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>You need to remember the differences between the <code>if</code> and <code>case</code> evaluations:</p>
<ul>
<li><code>if</code> block will be executed when the test condition <strong>evaluates to <code>true</code></strong></li>
<li><code>case</code> block will be executed when the test condition <strong>exactly matches</strong> the given <code>switch</code> argument</li>
</ul>
<h3 id="switchstatementusecases">Switch statement use cases</h3>
<p>The rule of thumb when you consider between <code>if</code> and <code>switch</code> is this:</p>
<blockquote>
<p>You only use <code>switch</code> when the code is cumbersome to write using <code>if</code></p>
</blockquote>
<p>For example, let's say you want to write a weekday name based on the weekday number</p>
<p>Here's how you can write it:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> weekdayNumber <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">0</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Sunday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">1</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Monday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">2</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Tuesday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">3</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Wednesday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">4</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Thursday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">5</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Friday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>weekdayNumber <span class="token operator">===</span> <span class="token number">6</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Saturday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The weekday number is invalid"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>I don't know about you, but the code above sure looks cumbersome to me! Although there's nothing wrong with the code above, you can make it prettier with <code>switch</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> weekdayNumber <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span>

<span class="token keyword">switch</span> <span class="token punctuation">(</span>weekdayNumber<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token number">0</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Sunday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">1</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Monday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">2</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Tuesday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">3</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Wednesday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">4</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Thursday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">5</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Friday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token number">6</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Saturday"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">default</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The weekday number is invalid"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>When you have lots of condition to evaluate for the same block, you'd probably combine multiple <code>if</code> conditions using the logical operator <strong>AND (<code>&amp;&amp;</code>)</strong> or <strong>OR(<code>||</code>)</strong>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myFood <span class="token operator">=</span> <span class="token string">"Banana"</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>myFood <span class="token operator">===</span> <span class="token string">"Banana"</span> <span class="token operator">||</span> myFood <span class="token operator">===</span> <span class="token string">"Apple"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Eat fruits everyday to keep you healthy."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>myFood <span class="token operator">===</span> <span class="token string">"Chocolate Cake"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Enjoy the sweet treat."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>You can replace the code above using the switch statement. The key is you need to stack multiple <code>cases</code> as one just like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myFood <span class="token operator">=</span> <span class="token string">"Banana"</span><span class="token punctuation">;</span>

<span class="token keyword">switch</span> <span class="token punctuation">(</span>myFood<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token string">"Banana"</span><span class="token operator">:</span>
  <span class="token keyword">case</span> <span class="token string">"Apple"</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Eat fruits everyday to keep you healthy."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token string">"Chocolate Cake"</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Enjoy the sweet treat."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Unfortunately, <code>switch</code> can't replace multiple <code>if</code> conditions that use the <code>&amp;&amp;</code> operator because of the way the <code>case</code> evaluation works. You need to use the <code>if</code> statement for that.</p>
<h3 id="exercise5">Exercise #5</h3>
<p>A primary school is giving different rewards based on the student's grade:</p>
<ul>
<li>Students that got an A will get a Chocolate</li>
<li>Students that got a B will get a Cookie</li>
<li>Students that got a C will get a Candy</li>
<li>For any other value, print "No reward to give."</li>
</ul>
<p>Create a variable named <code>grade</code> that will store the student's grade.</p>
<p>Example output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">You got an A, so here's a Chocolate for you!
You got a B, here's a Cookie for you!
You got a C, there's room for improvement and here's your Candy!
</code></pre>
<p>You can use either the <code>if...else</code> or the <code>switch...case</code> statement.</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="12controlflowsloopsinjavascript">12 - Control Flows (Loops) in JavaScript</h2>
<p>As you program an application in JavaScript, you'll often need to write a piece of code that needs to be executed repeatedly.</p>
<p>Let's say you want to write a program that prints the numbers 1 to 10 in the console. You can do it by calling <code>console.log</code> 10 times like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">4</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token number">5</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token comment">// and so on..</span>
</code></pre>
<p>This works, but there's a better way to write this kind of repetitive task.</p>
<p>A <strong>Loop statement</strong> is another category of control flow statement used to execute a block of code multiple times until a certain condition is met.</p>
<p>There are two loop statements used in JavaScript:</p>
<ul>
<li>The <code>for</code> statement</li>
<li>The <code>while</code> statement</li>
</ul>
<p>Let's learn how to use these statements in practice.</p>
<h3 id="theforstatement">The for statement</h3>
<p>Instead of repeating yourself 10 times to print the numbers 1 to 10, you can use the <code>for</code> statement and write just a single line of code as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> x <span class="token operator">&lt;</span> <span class="token number">10</span><span class="token punctuation">;</span> x<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>There you go! The <code>for</code> statement is followed by parentheses (<code>()</code>) which contain 3 expressions:</p>
<ul>
<li>The <code>initialization</code> expression, where you declare a variable to be used as the source of the loop condition. Represented as <code>x = 1</code> in the example.</li>
<li>The <code>condition</code> expression, where the variable in initialization will be evaluated for a specific condition. Represented as <code>x &lt; 11</code> in the example.</li>
<li>The <code>arithmetic</code> expression, where the variable value is either incremented or decremented by the end of each loop.</li>
</ul>
<p>These expressions are separated by a semicolon (<code>;</code>)</p>
<p>After the expressions, the curly brackets (<code>{}</code>) will be used to create a code block that will be executed by JavaScript as long as the <em><code>condition</code></em> expression returns <code>true</code>.</p>
<p>You can identify which expression is which by paying attention to the semicolon (<code>;</code>) which ends the statement.</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">for</span> <span class="token punctuation">(</span> <span class="token punctuation">[</span>initialization<span class="token punctuation">]</span><span class="token punctuation">;</span> <span class="token punctuation">[</span>condition<span class="token punctuation">]</span><span class="token punctuation">;</span> <span class="token punctuation">[</span>arithmetic expression<span class="token punctuation">]</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token comment">// As long as condition returns true,</span>
  <span class="token comment">// This block will be executed repeatedly</span>
<span class="token punctuation">}</span>
</code></pre>
<p>The arithmetic expression can be an increment (<code>++</code>) or a decrement (<code>--</code>) expression. It is run once each time the execution of the code inside the curly brackets end:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token number">10</span><span class="token punctuation">;</span> x <span class="token operator">&gt;=</span> <span class="token number">1</span><span class="token punctuation">;</span> x<span class="token operator">--</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Or you can also use shorthand arithmetic operators like <code>+=</code> and <code>-=</code> as shown below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// for statement with shorthand arithmetic expression</span>
<span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span> x <span class="token operator">&lt;</span> <span class="token number">20</span><span class="token punctuation">;</span> x <span class="token operator">+=</span> <span class="token number">3</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Here, the x will be incremented by 3 each time the loop is executed.</p>
<p>Once the loop is over, JavaScript will continue to execute any code you write below the <code>for</code> body:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> x <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span> x <span class="token operator">&lt;</span> <span class="token number">2</span><span class="token punctuation">;</span> x<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"The for loop has ended"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Continue code execution"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="whentouseaforloop">When to use a for loop</h3>
<p>The for loop is useful <strong>when you know how many times</strong> you need to execute a repetitive task.</p>
<p>For example, let's say you're writing a program to flip a coin. You need to find how many times the coin lands on heads when tossed 10 times. You can do it by using the <code>Math.random</code> method:</p>
<ul>
<li>When the number is lower than <code>0.5</code> you need to increment the <code>tails</code> counter</li>
<li>When the number is <code>0.5</code> and up you must increment the <code>heads</code> counter</li>
</ul>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> heads <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> tails <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>
<span class="token keyword">for</span> <span class="token punctuation">(</span>x <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span> x <span class="token operator">&lt;=</span> <span class="token number">10</span><span class="token punctuation">;</span> x<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">if</span> <span class="token punctuation">(</span>Math<span class="token punctuation">.</span><span class="token function">random</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token operator">&lt;</span> <span class="token number">0.5</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    tails<span class="token operator">++</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
    heads<span class="token operator">++</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
<span class="token punctuation">}</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Tossed the coin ten times"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Number of heads: </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>heads<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Number of tails: </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>tails<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>The example above shows where the <code>for</code> loop offers the most effective approach.</p>
<p>Now let's see an alternative exercise about coin flips where the <code>for</code> loop is not effective:</p>
<p><strong><em>Find out how many times you need to flip a coin until it lands on heads.</em></strong></p>
<p>This time, you don't know <strong>how many times</strong> you need to flip the coin. This is where you need to use the <code>while</code> loop statement, which you're going to learn next.</p>
<h3 id="thewhilestatement">The while statement</h3>
<p>The <code>while</code> statement or <code>while</code> loop is used to run a block of code as long as the condition evaluates to <code>true</code>.</p>
<p>You can define the condition and the statement for the loop as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">while</span> <span class="token punctuation">(</span>condition<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  statement<span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Just like the <code>for</code> loop, the <code>while</code> loop is used to execute a piece of code over and over again until it reaches the desired condition.</p>
<p>In the example below, below will keep executing the <em>statement</em> block until the <em>condition</em> expression returns <code>false</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>

<span class="token keyword">while</span> <span class="token punctuation">(</span>i <span class="token operator">&lt;</span> <span class="token number">6</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">The value of i = </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>i<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  i<span class="token operator">++</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Here, the <code>while</code> loop will repeatedly print the value of <code>i</code> as long as <code>i</code> is less than <code>6</code>. In each iteration, the value of <code>i</code> is incremented by 1 until it reaches 6 and the loop terminates.</p>
<p>Keep in mind that you need to include a piece of code that eventually turns the evaluating condition to <code>false</code> or the <code>while</code> loop will be executed forever. The example below will cause an infinite loop:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>

<span class="token keyword">while</span> <span class="token punctuation">(</span>i <span class="token operator">&lt;</span> <span class="token number">6</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">The value of i = </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>i<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Because the value of <code>i</code> never changes, the while loop will go on forever!</p>
<h3 id="whentouseawhileloop">When to use a while loop</h3>
<p>Seeing that both <code>while</code> and <code>for</code> can be used for executing a piece of code repeatedly, when should you use a <code>while</code> loop instead of <code>for</code>?</p>
<p>An easy way to know when you should use <code>while</code> is when <strong>you don't know how many times</strong> you need to execute the code.</p>
<p>Back to the coin toss example, there's one case that's perfect for a <code>while</code> loop:</p>
<p><strong><em>Find out how many times you need to flip a coin until it lands on heads.</em></strong></p>
<p>You also need to <strong>show how many times</strong> you flip the coin until it lands on heads:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> flips <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> isHeads <span class="token operator">=</span> <span class="token boolean">false</span><span class="token punctuation">;</span>

<span class="token keyword">while</span> <span class="token punctuation">(</span><span class="token operator">!</span>isHeads<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  flips<span class="token operator">++</span><span class="token punctuation">;</span>
  isHeads <span class="token operator">=</span> Math<span class="token punctuation">.</span><span class="token function">random</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token operator">&lt;</span> <span class="token number">0.5</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">It took </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>flips<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> flips to land on heads.</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Here, the condition <code>isHead = Math.random() &lt; 0.5</code> simulates the flipping of a fair coin. When the result is <code>true</code>, it means the coin landed on heads and the loop will exit.</p>
<p>Because you can't know how many times you need to loop until you get the number 8, you need to use a <code>while</code> loop instead of a <code>for</code> loop.</p>
<h3 id="exercise6">Exercise #6</h3>
<p>Write a program that prints a half pyramid using asterisks <code>*</code> as shown below:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">*
**
***
****
*****
</code></pre>
<p>Next, print a reverse half pyramid as follows:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">*****
****
***
**
*
</code></pre>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="13functionsinjavascript">13 - Functions in JavaScript</h2>
<p>A function is simply a section (or a block) of code that's written to perform a specific task.</p>
<p>For example, the type casting function <code>String()</code> is used to convert data of another type to a string.</p>
<p>The <code>console.log()</code> and various array methods we've learned in previous chapters are also functions. But because these functions are called from an object, they are called methods.</p>
<p>You'll learn more about methods later in Chapter 11. For now, just know that a function and a method are essentially the same, except that a method is called from an object.</p>
<p>Besides the built-in functions provided by JavaScript, you can also create your own function.</p>
<h3 id="howtocreateyourownfunction">How to create your own function</h3>
<p>Creating a function starts with typing the <code>function</code> keyword followed by the function name, a pair of round brackets, and then a pair of curly brackets.</p>
<p>Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token comment">// function body here</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>To call a function, you need to specify the function name followed by parentheses:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello!</span>
</code></pre>
<p>The code inside the function is executed when you call that function.</p>
<h3 id="functionparametersandarguments">Function parameters and arguments</h3>
<p>Parameters are variables used to accept inputs given when the function is called.</p>
<p>You can specify parameters in the function header, inside the parentheses.</p>
<p>The following example shows a function that has one parameter called <code>name</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token parameter">name</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token comment">// function body</span>
<span class="token punctuation">}</span>
</code></pre>
<p>How you use that <code>name</code> parameter inside the function is up to you.</p>
<p>You can use the parameter inside the <code>print()</code> function as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token parameter">name</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Nice weather today, right?"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Now whenever you need to call the <code>greet()</code> function, you need to pass an input to fill for the <code>name</code> parameter.</p>
<p>The input you passed to fill a parameter is called an argument, and here's how to do it:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token function">greet</span><span class="token punctuation">(</span><span class="token string">"Peter"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>The 'Peter' string inside the parentheses when calling the <code>greet()</code> function will be passed as the <code>name</code> parameter.</p>
<p>Run the code to receive this output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello, Peter!
Nice weather today, right?
</code></pre>
<p>You can have more than one parameter when defining the function, but you need to split each parameter with a comma as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token parameter">name<span class="token punctuation">,</span> weather</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">It's </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>weather<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> today, right?</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token string">"Nathan"</span><span class="token punctuation">,</span> <span class="token string">"rainy"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello, Nathan!
It's rainy today, right?
</code></pre>
<p>When you specify two parameters in the function header, you need to pass two arguments. If you call the function without passing the arguments then the value will be <code>undefined</code>.</p>
<p>In the next section, you'll learn how to create parameters with default values, which allows you to call the function without having to pass an argument to it.</p>
<p>But for now, I hope you see the convenience of having parameters. They make your functions more adaptable and reusable by taking different input values to cover a variety of scenarios the function might have.</p>
<p>As shown in the example, the <code>name</code> and <code>weather</code> parameters allow you to greet many different people in different weathers.</p>
<p>Whether sunny, rainy, or cloudy, just change the <code>name</code> and <code>weather</code> arguments when you want to greet another person.</p>
<h3 id="defaultparameters">Default parameters</h3>
<p>When defining a function, you can set a default value for any parameter in that function.</p>
<p>For example, the <code>name</code> parameter in the function below is a default parameter:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span>name <span class="token operator">=</span> <span class="token string">"Nathan"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Nice weather today, right?"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Here, the default value 'Nathan' will be used when no value or <code>undefined</code> is passed for the <code>name</code> parameter.</p>
<p>You can test this by calling the <code>greet()</code> function without an argument as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token function">greet</span><span class="token punctuation">(</span><span class="token string">"Jack"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello, Nathan!
Nice weather today, right?

Hello, Jack!
Nice weather today, right?
</code></pre>
<p>Any function you define can have a mix of default and non-default parameters.</p>
<p>Here's another example of a function that has one default parameter called <code>name</code> and one non-default parameter called <code>weather</code>:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span>weather<span class="token punctuation">,</span> name <span class="token operator">=</span> <span class="token string">"Nathan"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">It's </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>weather<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> today, right?</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token string">"sunny"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello, Nathan!
It's sunny today, right?
</code></pre>
<p>Notice that the <code>weather</code> parameter was placed in front of the <code>name</code> parameter. This is for convenience so that you don't need to specify the default parameter.</p>
<p>If you place the non-default parameter after the default parameter, then you need to pass a value to the <code>name</code> parameter to get to the <code>weather</code> parameter.</p>
<p>Consider the example below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span>name <span class="token operator">=</span> <span class="token string">"Nathan"</span><span class="token punctuation">,</span> weather<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">It's </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>weather<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> today, right?</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token keyword">undefined</span><span class="token punctuation">,</span> <span class="token string">"sunny"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>To pass an argument to the <code>weather</code> parameter, we need to pass <code>undefined</code> or any value for the <code>name</code> parameter first.</p>
<p>This is why it's better to specify non-default parameters in front of default parameters.</p>
<h3 id="defaultparametersandnull">Default parameters and null</h3>
<p>Back in Section 2, recall that we briefly explored the difference between <code>undefined</code> as the "default" empty value and <code>null</code> as the "intentional" empty value.</p>
<p>When you pass <code>undefined</code> to a function that has a default parameter, the default parameter will be used:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span>name <span class="token operator">=</span> <span class="token string">"John"</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>name<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token keyword">undefined</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// John</span>
</code></pre>
<p>As you can see, JavaScript prints the default parameter value <code>John</code> when you pass <code>undefined</code> to the function.</p>
<p>But when you pass <code>null</code> to the function, the default parameter will be ignored:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span>name <span class="token operator">=</span> <span class="token string">"John"</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>name<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token keyword">null</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// null</span>
</code></pre>
<p>This is one of the common mistakes that beginners make when learning JavaScript. When you use the value <code>null</code>, JavaScript will think you want that value to be empty, so it doesn't replace the value with the default parameter.</p>
<p>When you use <code>undefined</code>, then JavaScript will replace it with the default parameter. You might encounter this issue as you work with JavaScript code in your career, so just keep this in mind.</p>
<h3 id="thereturnstatement">The return statement</h3>
<p>A function can also have a <code>return</code> statement inside the code block. A <code>return</code> statement is used to return a value back to the caller.</p>
<p>For example, the following function returns the sum of two values:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">sum</span><span class="token punctuation">(</span><span class="token parameter">a<span class="token punctuation">,</span> b</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> a <span class="token operator">+</span> b<span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token keyword">let</span> result <span class="token operator">=</span> <span class="token function">sum</span><span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>result<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// 5</span>
</code></pre>
<p>The value returned by a function can be assigned to a variable for further operation. You can add the <code>return</code> statement anywhere inside the function.</p>
<p>When JavaScript reaches the <code>return</code> statement, it skips further code written inside the function block and goes back to where you call the function.</p>
<p>The following function has two return statements:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">checkAge</span><span class="token punctuation">(</span><span class="token parameter">age</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">if</span> <span class="token punctuation">(</span>age <span class="token operator">&gt;</span> <span class="token number">18</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">return</span> <span class="token string">"You may get a car license"</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
  <span class="token keyword">return</span> <span class="token string">"You may not get a car license yet"</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token function">checkAge</span><span class="token punctuation">(</span><span class="token number">20</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token function">checkAge</span><span class="token punctuation">(</span><span class="token number">15</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">You may get a car license
You may not get a car license yet
</code></pre>
<p>When we call the <code>checkAge()</code> function the first time, the value of <code>age</code> argument is greater than 18, so JavaScript executes the <code>return</code> statement inside the <code>if</code> block.</p>
<p>The second time we called the function, the <code>if</code> condition isn't met, so JavaScript executes the <code>return</code> statement under the <code>if</code> block instead.</p>
<p>You can also stop a function execution and return to the caller by specifying the <code>return</code> statement without any value:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token keyword">return</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Good bye!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
</code></pre>
<p>Output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Hello!
</code></pre>
<p>Here, the <code>return</code> statement is called between the <code>console.log()</code> calls.</p>
<p>JavaScript executes the first <code>console.log()</code> call, then skips the rest of the code. The 'Good bye!' string isn't printed.</p>
<h3 id="variablescope">Variable scope</h3>
<p>Now that you're learning about functions, it's a good time to talk about variable scope.</p>
<p>A variable declared inside a function can only be accessed from that function. This is because that variable has a local scope.</p>
<p>On the other hand, a variable declared outside of any block is known as a global variable because of its global scope.</p>
<p>These two scopes are important because when you try to access a local variable outside of its scope, you'll get an error. For example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">let</span> myString <span class="token operator">=</span> <span class="token string">"Hello World!"</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myString<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>When you run the code above, JavaScript responds with an error:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">ReferenceError: myString is not defined
</code></pre>
<p>This is because the <code>myString</code> variable is declared inside the <code>greet()</code> function, so you can't access that variable outside of it. It doesn't matter even if you called that function before accessing the variable.</p>
<p>Meanwhile, a global variable can be accessed from anywhere, even inside a function:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myString <span class="token operator">=</span> <span class="token string">"Hello World!"</span><span class="token punctuation">;</span>

<span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myString<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello World!</span>
</code></pre>
<p>Here, the <code>greet()</code> function is able to access the <code>myString</code> variable declared outside of it.</p>
<p>Keep in mind that this applies only to variables declared using <code>let</code> and <code>const</code>.</p>
<p>Next, you can also define a local variable with the same name as the global variable without overwriting it.</p>
<p>Here's an example:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myString <span class="token operator">=</span> <span class="token string">"Hello World!"</span><span class="token punctuation">;</span>

<span class="token keyword">function</span> <span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">let</span> myString <span class="token operator">=</span> <span class="token string">"Morning!"</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myString<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>  <span class="token comment">// Morning!</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myString<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello World!</span>
</code></pre>
<p>When you call the <code>greet()</code> function, a local variable called <code>myString</code> was assigned the string 'Morning!'.</p>
<p>Outside of the function, the global variable that's also called <code>myString</code> still exists, and the value isn't changed.</p>
<p>JavaScript considers the local scope variable to be a different variable. When you declare the same variable inside a function, any code inside the function will always refer to the local variable.</p>
<p>In practice, you rarely need to declare the same variable in different scopes:</p>
<ol>
<li>Any variable declared outside a function shouldn't be used inside a function without passing them as parameters.</li>
<li>A variable declared inside a function should never be referred to outside of that function</li>
</ol>
<p>Keep this in mind when you write JavaScript functions.</p>
<h3 id="therestparameter">The rest parameter</h3>
<p>The rest parameter is a parameter that can accept any number of data as its arguments. The arguments will be stored as an array.</p>
<p>You can define a rest parameter in the function header by adding triple dots <code>...</code> before the parameter name.</p>
<p>Here's an example of creating a function that has a variable length argument:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">printArguments</span><span class="token punctuation">(</span><span class="token parameter"><span class="token operator">...</span>args</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>args<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>When calling the <code>printArguments()</code> function above, you can specify as many arguments as you want:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">printArguments</span><span class="token punctuation">(</span><span class="token parameter"><span class="token operator">...</span>args</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>args<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">printArguments</span><span class="token punctuation">(</span><span class="token string">"A"</span><span class="token punctuation">,</span> <span class="token string">"B"</span><span class="token punctuation">,</span> <span class="token string">"C"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token comment">// [ 'A', 'B', 'C' ]</span>
<span class="token function">printArguments</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">4</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// [ 1, 2, 3, 4, 5 ]</span>
</code></pre>
<p>Keep in mind that a function can only have one rest parameter, and the rest parameter must be the last parameter in the function.</p>
<p>You can use a rest parameter when your function needs to work with an indefinite number of arguments.</p>
<h3 id="arrowfunction">Arrow function</h3>
<p>The <strong>JavaScript arrow function syntax</strong> allows you to write a JavaScript function with a shorter, more concise syntax.</p>
<p>When you need to create a function in JavaScript, the primary method is to use the <code>function</code> keyword followed by the function name as shown below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">greetings</span><span class="token punctuation">(</span><span class="token parameter">name</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">greetings</span><span class="token punctuation">(</span><span class="token string">"John"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello, John!</span>
</code></pre>
<p>The arrow function syntax allows you to create a function expression that produces the same result as the code above.</p>
<p>Here's the <code>greetings()</code> function using the arrow syntax:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">greetings</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter">name</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello, </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string">!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

<span class="token function">greetings</span><span class="token punctuation">(</span><span class="token string">"John"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// Hello, John!</span>
</code></pre>
<p>When you create a function using the arrow function syntax, you need to assign the expression to a variable so that the function has a name.</p>
<p>Basically, the arrow function syntax looks as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">fun</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter">param1<span class="token punctuation">,</span> param2<span class="token punctuation">,</span> <span class="token operator">...</span></span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
  <span class="token comment">// function body</span>
<span class="token punctuation">}</span>
</code></pre>
<p>In the code above,</p>
<ul>
<li><code>fun</code> is the variable that holds the function. You can call the function as <code>fun()</code> later in your code.</li>
<li><code>(param1, param2, ...)</code> are the function parameters. You can define as many parameters as required by the function.</li>
<li>Then you have the arrow <code>=&gt;</code> to indicate the beginning of the function.</li>
</ul>
<p>The code above is equal to the following:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">fun</span> <span class="token operator">=</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token parameter">param1<span class="token punctuation">,</span> param2<span class="token punctuation">,</span> <span class="token operator">...</span></span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token comment">// function body</span>
<span class="token punctuation">}</span>
</code></pre>
<p>The arrow function syntax doesn't add any new ability to the JavaScript language.</p>
<p>Instead, it offers improvements to the way you write a function in JavaScript.</p>
<p>At first, it may seem weird as you are used to the <code>function</code> keyword.</p>
<p>But as you start using the arrow syntax, you will see that it's very convenient and easier to write.</p>
<h3 id="singleandmultilinearrowfunctions">Single and multiline arrow functions</h3>
<p>The arrow function provides you a way to write a single line function where the left side of the arrow <code>=&gt;</code> is returned to the right side.</p>
<p>When you use the <code>function</code> keyword, you need to use the curly brackets <code>{}</code> and the <code>return</code> keyword as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">plusTwo</span><span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Using the arrow function, you can omit both the curly brackets and the <code>return</code> keyword, creating a single line function as shown below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">plusTwo</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
</code></pre>
<p>Without the curly brackets, JavaScript will evaluate the expression on the right side of the arrow syntax and return it to the caller.</p>
<p>The arrow function syntax also works for a function that doesn't <code>return</code> a value as shown below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">greetings</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>When using the arrow function syntax, the curly brackets are required only when you have a multiline function body:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">greetings</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"How are you?"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="arrowfunctionwithoutroundbrackets">Arrow function without round brackets</h3>
<p>The round brackets <code>()</code> are used in JavaScript functions to indicate the parameters that the function can receive.</p>
<p>When you use the <code>function</code> keyword, the round brackets are always required:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">plusThree</span><span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">3</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>On the other hand, the arrow function allows you to omit the round brackets when you have <strong>exactly one parameter</strong> for the function:</p>
<p>The following code example is a valid arrow function expression:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">plusThree</span> <span class="token operator">=</span> <span class="token parameter">num</span> <span class="token operator">=&gt;</span> num <span class="token operator">+</span> <span class="token number">3</span><span class="token punctuation">;</span>
</code></pre>
<p>As you can see, you can remove the round and curly brackets as well as the <code>return</code> keyword.</p>
<p>But you still need the round brackets for two conditions:</p>
<ul>
<li>When the function has no parameter</li>
<li>When the function has more than one parameter</li>
</ul>
<p>When you have no parameter, then you need round brackets before the arrow as shown below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">greetings</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>The same applies when you have more than one parameter.</p>
<p>The function below has two parameters: <code>name</code> and <code>age</code>.</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">greetings</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter">name<span class="token punctuation">,</span> age</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Hello World!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>The arrow syntax makes the round brackets optional when you have a single parameter function.</p>
<h3 id="arrowfunctiondoesnthaveargumentsbinding">Arrow function doesn't have arguments binding</h3>
<p>When using the <code>function</code> keyword to define a function, you can access the arguments you pass to the function using the <code>arguments</code> keyword like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">printArgs</span> <span class="token operator">=</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>arguments<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

<span class="token function">printArgs</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// [Arguments] { '0': 1, '1': 2, '2': 3 }</span>
</code></pre>
<p>The <code>arguments</code> keyword in the code above refers to the object that stores all the arguments you passed into the function.</p>
<p>By contrast, the arrow function doesn't have the <code>arguments</code> object and will throw an error when you try to access it:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">printArgs</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>arguments<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token function">printArgs</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">//Uncaught ReferenceError: arguments is not defined</span>
</code></pre>
<p>You can use the JavaScript spread syntax to imitate the <code>arguments</code> binding as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> <span class="token function-variable function">printArgs</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter"><span class="token operator">...</span>arguments</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>arguments<span class="token punctuation">)</span><span class="token punctuation">;</span>

<span class="token function">printArgs</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token comment">// [1, 2, 3]</span>
</code></pre>
<p>By using the spread syntax, the arguments you passed to the arrow function will be stored in an array.</p>
<p><strong>Note</strong> that you need the round brackets even though you are passing just one argument to the function.</p>
<p>You can access the given <code>arguments</code> with the array index notation as <code>arguments[0]</code>, <code>arguments[1]</code>, and so on.</p>
<h3 id="howtoconvertanormalfunctiontoanarrowfunctioneasily">How to convert a normal function to an arrow function easily</h3>
<p>You can follow the <strong>three easy steps</strong> below to convert a normal function to an arrow function:</p>
<ol>
<li>Replace the <code>function</code> keyword with the variable keyword <code>let</code> or <code>const</code></li>
<li>Add <code>=</code> symbol after the function name and before the round brackets</li>
<li>Add <code>=&gt;</code> symbol after the round brackets</li>
</ol>
<p>The code below will help you to visualize the steps:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">plusTwo</span><span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">// step 1: replace function with let / const</span>
<span class="token keyword">const</span> <span class="token function">plusTwo</span><span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">// step 2: add = after the function name</span>
<span class="token keyword">const</span> plusTwo <span class="token operator">=</span> <span class="token punctuation">(</span>num<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token comment">// step 3: add =&gt; after the round brackets</span>
<span class="token keyword">const</span> <span class="token function-variable function">plusTwo</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>The three steps above are enough to convert any old JavaScript function syntax to the new arrow function syntax.</p>
<p>When you have a single line function, there's a fourth optional step to remove the curly brackets and the <code>return</code> keyword as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// from this</span>
<span class="token keyword">const</span> <span class="token function-variable function">plusTwo</span> <span class="token operator">=</span> <span class="token parameter">num</span> <span class="token operator">=&gt;</span> <span class="token punctuation">{</span>
  <span class="token keyword">return</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

<span class="token comment">// to this</span>
<span class="token keyword">const</span> <span class="token function-variable function">plusTwo</span> <span class="token operator">=</span> <span class="token parameter">num</span> <span class="token operator">=&gt;</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
</code></pre>
<p>When you have exactly one parameter, you can also remove the round brackets:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token comment">// from this</span>
<span class="token keyword">const</span> <span class="token function-variable function">plusTwo</span> <span class="token operator">=</span> <span class="token punctuation">(</span><span class="token parameter">num</span><span class="token punctuation">)</span> <span class="token operator">=&gt;</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>

<span class="token comment">// to this</span>
<span class="token keyword">const</span> <span class="token function-variable function">plusTwo</span> <span class="token operator">=</span> <span class="token parameter">num</span> <span class="token operator">=&gt;</span> num <span class="token operator">+</span> <span class="token number">2</span><span class="token punctuation">;</span>
</code></pre>
<p>But the last two steps are optional. Only the first three steps are required to convert any JavaScript <code>function</code> and use the arrow function syntax.</p>
<h3 id="exercise7">Exercise #7</h3>
<p>Write a function named <code>calculateSquare()</code> that's used to calculate the area and perimeter of a square shape.</p>
<p>The function accepts one parameter: the <code>side</code> of the square.</p>
<p>The formula to calculate the area is <code>side * side</code>, and the formula to calculate the perimeter is <code>4 * side</code>.</p>
<p>The output shows the size of the size, the area, and the perimeter as follows:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">The square side is 8
The area of the square is 64
The perimeter of the square is 32
</code></pre>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="14objectsinjavascript">14 - Objects in JavaScript</h2>
<p>An object is a special data type that allows you to store more than one value, just like an array.</p>
<p>The difference between an object and an array is that an array stores data as a list of items, while an object stores data in a <code>key:value</code> pair format.</p>
<p>Let's see an example illustrating this difference. Suppose you want to store information about a book in your program.</p>
<p>When you use regular variables, it would look like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> bookTitle <span class="token operator">=</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> bookAuthor <span class="token operator">=</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">;</span>
</code></pre>
<p>While it works fine, it certainly isn't the best way to store related values.</p>
<p>Another way to store the value would be to use an array:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
</code></pre>
<p>This is certainly better as you can group related data about the book together, but you have no way to add context to the value.</p>
<p>This is where an object is useful. You can declare a single book object and store the data in <code>key:value</code> format:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>
</code></pre>
<p>An object is declared using the curly brackets <code>{}</code>, and each item inside the brackets is written in the <code>key:value</code> format.</p>
<p>An object item is also known as a property, with the <em>key</em> as property name and <em>value</em> as property value.</p>
<p>Like an array, you need to separate each item inside an object using a comma.</p>
<p>You can assign a string or numbers as the key of an item, and you can assign any type of data as the value, including a function:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
  <span class="token function-variable function">describe</span><span class="token operator">:</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Book title: </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span><span class="token keyword">this</span><span class="token punctuation">.</span>title<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Book author: </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span><span class="token keyword">this</span><span class="token punctuation">.</span>author<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>
</code></pre>
<p>Here, the <code>describe</code> key or property is a function that prints the <code>title</code> and <code>author</code> value from the object.</p>
<p>The <code>this</code> keyword refers to the context of the code, which is the <code>myBook</code> object in this case.</p>
<p>Usually, an object key is something that gives more context to the value it holds. A key must also be unique, so you can't use the same key twice in the same object.</p>
<p>For example, if you have data about a book, you can use object keys such as <code>title</code>, <code>author</code>, and <code>price</code> to help you understand the context of the value stored in each key.</p>
<h3 id="howtoaccessobjectvalues">How to access object values</h3>
<p>To access the value of an object, you can use either the dot notation <code>.</code> or the square brackets <code>[]</code> notation.</p>
<p>Here's an example of using the dot notation to access the object properties:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">.</span>title<span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">.</span>author<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>And here's how you use the square brackets to access the same properties:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">[</span><span class="token string">"title"</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">[</span><span class="token string">"author"</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Keep in mind that you need to wrap the property name in quotes like a string, or JavaScript will think you're passing a variable inside the square brackets.</p>
<h3 id="howtoaddanewpropertytotheobject">How to add a new property to the object</h3>
<p>You can assign a new property to the object using either the dot notation or the square brackets like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

<span class="token comment">// add release year property</span>
myBook<span class="token punctuation">.</span>year <span class="token operator">=</span> <span class="token number">2023</span><span class="token punctuation">;</span>

<span class="token comment">// add publisher property</span>
myBook<span class="token punctuation">[</span><span class="token string">"publisher"</span><span class="token punctuation">]</span> <span class="token operator">=</span> <span class="token string">"CodeWithNathan"</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>When you print the object, here's the result:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">{
  title: 'JavaScript Introduction',
  author: 'Nathan Sebhastian',
  year: 2023,
  publisher: 'CodeWithNathan'
}
</code></pre>
<p>You can add as many properties as you need to the same object.</p>
<h3 id="howtomodifyobjectproperties">How to modify object properties</h3>
<p>To modify an existing property, you need to specify an existing object property using either the dot or square brackets notation followed by the assignment operator as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

<span class="token comment">// change the author property</span>
myBook<span class="token punctuation">.</span>author <span class="token operator">=</span> <span class="token string">"John Doe"</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">{
  title: 'JavaScript Introduction',
  author: 'John Doe'
}
</code></pre>
<p>As you can see, the <code>author</code> property value has been changed.</p>
<h3 id="howtodeleteobjectproperties">How to delete object properties</h3>
<p>To delete a property from your object, you need to use the <code>delete</code> operator as follows:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> myBook <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">title</span><span class="token operator">:</span> <span class="token string">"JavaScript Introduction"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">author</span><span class="token operator">:</span> <span class="token string">"Nathan Sebhastian"</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

<span class="token keyword">delete</span> myBook<span class="token punctuation">.</span>author<span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>myBook<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p><strong>Output:</strong></p>
<pre class="language-txt" tabindex="0"><code class="language-txt">{ title: 'JavaScript Introduction' }
</code></pre>
<p>When you try to access the deleted property, you will get the <code>undefined</code> value.</p>
<h3 id="howtocheckifapropertyexistsinanobject">How to check if a property exists in an object</h3>
<p>To check if a certain property exists in your object, you can use the <code>in</code> operator like this:</p>
<pre class="language-js" tabindex="0"><code class="language-js">propertyName <span class="token keyword">in</span> myObject
</code></pre>
<p>The <code>in</code> operator returns <code>true</code> if the <code>propertyName</code> exists in your object.</p>
<p>See the example below:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> person <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">firstName</span><span class="token operator">:</span> <span class="token string">"Nathan"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">lastName</span><span class="token operator">:</span> <span class="token string">"Sebhastian"</span>
<span class="token punctuation">}</span>

<span class="token comment">// check if firstName exists</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">'firstName'</span> <span class="token keyword">in</span> person<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// true</span>

<span class="token comment">// check if age exists</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">'age'</span> <span class="token keyword">in</span> person<span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token comment">// false</span>
</code></pre>
<p>Now you know how to manipulate a JavaScript object.</p>
<h3 id="exercise8">Exercise #8</h3>
<p>Create a <code>person</code> object with the following properties:</p>
<ul>
<li><code>name</code> - the person's name</li>
<li><code>age</code> - the person's age</li>
<li><code>greet()</code> - a function to greet another person</li>
</ul>
<p>Inside the <code>greet()</code> function, introduce the person, specifying the name and the age.</p>
<p>Here's an example output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">person.greet();

Hello! My name is Alex and I'm 22 years old.
</code></pre>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="finalexercisebuildacashregistermachine">Final Exercise: Build a Cash Register Machine</h2>
<p>Let's build a cash register machine that can add items to a shopping cart, calculate total price, calculate discounts, and accept payment by cash.</p>
<p>The currency is assumed in USD, so you don't need to add it to the program.</p>
<p>The cash register has 3 items for sale:</p>
<ul>
<li>Phone for 300</li>
<li>Smart TV for 220</li>
<li>Gaming Console for 150</li>
</ul>
<p>There's a 10% discount when the total price is higher than 400.</p>
<p>The cash register should have a shopping cart that starts empty.</p>
<p>The cash register should provide a method called <code>addItem</code> that takes the name of an item as a parameter. When called, it should check if the item is available for sale. If it is, the item should be added to the shopping cart. If it is not available, show a message saying we don't sell that item.</p>
<p>The cash register should provide a method called <code>calculateTotalPrice</code> that calculates the total price of all the items in the shopping cart. It should iterate over the items in the shopping cart and sum up their prices.</p>
<p>The cash register should provide a method called <code>pay</code> that takes the payment amount as a parameter.</p>
<p>It should calculate the total price of the items in the shopping cart using the <code>calculateTotalPrice</code> method. If the total price is higher than 400, a 10% discount should be applied.</p>
<p>The method should then compare the payment amount with the total price (after applying the discount) and display an appropriate message:</p>
<ul>
<li>If the payment amount is equal to or greater than the total price, it should display a message thanking the customer for the purchase. If there is any change, it should also display the amount of change to be given.</li>
<li>If the payment amount is less than the total price, it should display a message indicating that the customer does not have enough money to purchase the items.</li>
<li>The program should include appropriate <code>console.log()</code> statements to display messages for adding items to the shopping cart, displaying the total price, and processing the payment.</li>
</ul>
<p>The program should handle scenarios where the customer's payment amount is exactly equal to the total price, as well as cases where the payment amount is greater or less than the total price.</p>
<p>To build the program, you need to use what you've learned about objects, arrays, conditionals, and loops.</p>
<p>I recommend that you try building the program yourself first. If you get stuck, then see the provided solution below. Good luck!</p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="conclusion">Conclusion</h2>
<p>Congratulations on finishing this handbook! We have gone through quite a lot of concepts together to learn how to code using JavaScript.</p>
<p>I hope you enjoyed the process as much as I enjoy writing it. I would love to get your feedback, learning what you liked and didn't so I can improve the tutorial.</p>
<p>If you want to learn more about JavaScript, I'm creating a course that helps you use JavaScript to build web applications. It's currently in a pre-order period so you can get the course at a lower price and support my work in creating more tutorials. You can <a href="https://codewithnathan.com/js-course">check it out here</a>.</p>
<p><a href="https://codewithnathan.com/js-course"><img src="https://www.freecodecamp.org/news/content/images/2023/07/nathan-js-tutorial.jpg" alt="The JavaScript Tutorial by Nathan Sebhastian" loading="lazy" width="1200" height="840"></a></p>
<!--kg-card-end: markdown--><!--kg-card-begin: markdown--><h2 id="solutions">Solutions</h2>
<h3 id="exercise1">Exercise #1</h3>
<pre class="language-js" tabindex="0"><code class="language-js">console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Your name here"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Your age here"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"Your occupation here"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="exercise2">Exercise #2</h3>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> name <span class="token operator">=</span> <span class="token string">"Your name here"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> age <span class="token operator">=</span> <span class="token string">"Your age here"</span><span class="token punctuation">;</span>
<span class="token keyword">let</span> occupation <span class="token operator">=</span> <span class="token string">"Your occupation here"</span><span class="token punctuation">;</span>

console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>name<span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>age<span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>occupation<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="exercise3">Exercise #3</h3>
<pre class="language-txt" tabindex="0"><code class="language-txt">1
false
true
true
true
false
</code></pre>
<h3 id="exercise4">Exercise #4</h3>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> colors <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token string">"red"</span><span class="token punctuation">,</span> <span class="token string">"green"</span><span class="token punctuation">,</span> <span class="token string">"blue"</span><span class="token punctuation">]</span><span class="token punctuation">;</span>

colors<span class="token punctuation">.</span><span class="token function">push</span><span class="token punctuation">(</span><span class="token string">"black"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>colors<span class="token punctuation">)</span><span class="token punctuation">;</span>

colors<span class="token punctuation">.</span><span class="token function">shift</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
colors<span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span> <span class="token operator">=</span> <span class="token string">"blue"</span><span class="token punctuation">;</span>
colors<span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span> <span class="token operator">=</span> <span class="token string">"green"</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>colors<span class="token punctuation">)</span><span class="token punctuation">;</span>

colors<span class="token punctuation">.</span><span class="token function">unshift</span><span class="token punctuation">(</span><span class="token string">"yellow"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>colors<span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="exercise5">Exercise #5</h3>
<p>Using <code>if...else</code> statement:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> grade <span class="token operator">=</span> <span class="token string">"A"</span><span class="token punctuation">;</span>

<span class="token keyword">if</span> <span class="token punctuation">(</span>grade <span class="token operator">===</span> <span class="token string">"A"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You got an A, so here's a Chocolate for you!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>grade <span class="token operator">===</span> <span class="token string">"B"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You got a B, here's a Cookie for you!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token keyword">if</span> <span class="token punctuation">(</span>grade <span class="token operator">===</span> <span class="token string">"C"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>
    <span class="token string">"You got a C, there's room for improvement and here's your Candy!"</span>
  <span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"No reward to give."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> grade <span class="token operator">=</span> <span class="token string">"A"</span><span class="token punctuation">;</span>
<span class="token keyword">switch</span> <span class="token punctuation">(</span>grade<span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">case</span> <span class="token string">"A"</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You got an A, so here's a Chocolate for you!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token string">"B"</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"You got a B, here's a Cookie for you!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">case</span> <span class="token string">"C"</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>
      <span class="token string">"You got a C, there's room for improvement and here's your Candy!"</span>
    <span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">break</span><span class="token punctuation">;</span>
  <span class="token keyword">default</span><span class="token operator">:</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token string">"No reward to give."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Using <code>switch...case</code> statement:</p>
<h3 id="exercise6">Exercise #6</h3>
<p>Half pyramid pattern:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">let</span> pattern<span class="token punctuation">;</span>

<span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> i <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span> i <span class="token operator">&lt;=</span> <span class="token number">5</span><span class="token punctuation">;</span> i<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  pattern <span class="token operator">=</span> <span class="token string">""</span><span class="token punctuation">;</span>
  <span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> j <span class="token operator">=</span> <span class="token number">1</span><span class="token punctuation">;</span> j <span class="token operator">&lt;=</span> i<span class="token punctuation">;</span> j<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    pattern <span class="token operator">+=</span> <span class="token string">"*"</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>pattern<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Inverse half pyramid pattern:</p>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> i <span class="token operator">=</span> <span class="token number">4</span><span class="token punctuation">;</span> i <span class="token operator">&gt;=</span> <span class="token number">0</span><span class="token punctuation">;</span> i<span class="token operator">--</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  pattern <span class="token operator">=</span> <span class="token string">""</span><span class="token punctuation">;</span>
  <span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">let</span> j <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> j <span class="token operator">&lt;=</span> i<span class="token punctuation">;</span> j<span class="token operator">++</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    pattern <span class="token operator">+=</span> <span class="token string">"*"</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>pattern<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<h3 id="exercise7">Exercise #7</h3>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">function</span> <span class="token function">calculateSquare</span><span class="token punctuation">(</span><span class="token parameter">side</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">The square side is </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>side<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">The area of the square is </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>side <span class="token operator">*</span> side<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">The perimeter of the square is </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span><span class="token number">4</span> <span class="token operator">*</span> side<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>

<span class="token function">calculateSquare</span><span class="token punctuation">(</span><span class="token number">7</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="exercise8">Exercise #8</h3>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> person <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">name</span><span class="token operator">:</span> <span class="token string">"Alex"</span><span class="token punctuation">,</span>
  <span class="token literal-property property">age</span><span class="token operator">:</span> <span class="token number">22</span><span class="token punctuation">,</span>
  <span class="token function-variable function">greet</span><span class="token operator">:</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>
      <span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Hello! My name is </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span><span class="token keyword">this</span><span class="token punctuation">.</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> and I'm </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span><span class="token keyword">this</span><span class="token punctuation">.</span>age<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> years old.</span><span class="token template-punctuation string">`</span></span>
    <span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>

person<span class="token punctuation">.</span><span class="token function">greet</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<h3 id="finalexercise">Final Exercise</h3>
<pre class="language-js" tabindex="0"><code class="language-js"><span class="token keyword">const</span> cashRegister <span class="token operator">=</span> <span class="token punctuation">{</span>
  <span class="token literal-property property">itemsForSale</span><span class="token operator">:</span> <span class="token punctuation">[</span>
    <span class="token punctuation">{</span> <span class="token literal-property property">name</span><span class="token operator">:</span> <span class="token string">"Phone"</span><span class="token punctuation">,</span> <span class="token literal-property property">price</span><span class="token operator">:</span> <span class="token number">300</span> <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">{</span> <span class="token literal-property property">name</span><span class="token operator">:</span> <span class="token string">"Smart TV"</span><span class="token punctuation">,</span> <span class="token literal-property property">price</span><span class="token operator">:</span> <span class="token number">220</span> <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">{</span> <span class="token literal-property property">name</span><span class="token operator">:</span> <span class="token string">"Gaming Console"</span><span class="token punctuation">,</span> <span class="token literal-property property">price</span><span class="token operator">:</span> <span class="token number">150</span> <span class="token punctuation">}</span><span class="token punctuation">,</span>
  <span class="token punctuation">]</span><span class="token punctuation">,</span>
  <span class="token literal-property property">shoppingCart</span><span class="token operator">:</span> <span class="token punctuation">[</span><span class="token punctuation">]</span><span class="token punctuation">,</span>
  <span class="token function-variable function">addItem</span><span class="token operator">:</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token parameter">name</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">let</span> foundItem <span class="token operator">=</span> <span class="token keyword">this</span><span class="token punctuation">.</span>itemsForSale<span class="token punctuation">.</span><span class="token function">find</span><span class="token punctuation">(</span><span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token parameter">item</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
      <span class="token keyword">return</span> item<span class="token punctuation">.</span>name <span class="token operator">===</span> name<span class="token punctuation">;</span>
    <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">if</span> <span class="token punctuation">(</span>foundItem<span class="token punctuation">)</span> <span class="token punctuation">{</span>
      <span class="token keyword">this</span><span class="token punctuation">.</span>shoppingCart<span class="token punctuation">.</span><span class="token function">push</span><span class="token punctuation">(</span>foundItem<span class="token punctuation">)</span><span class="token punctuation">;</span>
      console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Adding </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> to your shopping cart</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
      console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Sorry, we don't sell </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>name<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> here!</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
  <span class="token function-variable function">calculateTotalPrice</span><span class="token operator">:</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">let</span> totalPriceAmount <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>
    <span class="token keyword">this</span><span class="token punctuation">.</span>shoppingCart<span class="token punctuation">.</span><span class="token function">forEach</span><span class="token punctuation">(</span><span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token parameter">purchasedItem</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
      totalPriceAmount <span class="token operator">+=</span> purchasedItem<span class="token punctuation">.</span>price<span class="token punctuation">;</span>
    <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">return</span> totalPriceAmount<span class="token punctuation">;</span>
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
  <span class="token function-variable function">pay</span><span class="token operator">:</span> <span class="token keyword">function</span> <span class="token punctuation">(</span><span class="token parameter">amount</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">let</span> totalPriceAmount <span class="token operator">=</span> <span class="token keyword">this</span><span class="token punctuation">.</span><span class="token function">calculateTotalPrice</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">if</span> <span class="token punctuation">(</span>totalPriceAmount <span class="token operator">&gt;</span> <span class="token number">500</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
      totalPriceAmount <span class="token operator">-=</span> totalPriceAmount <span class="token operator">*</span> <span class="token number">0.1</span><span class="token punctuation">;</span>
      console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>
        <span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">You get a 10% discount and your total price is </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>totalPriceAmount<span class="token interpolation-punctuation punctuation">}</span></span><span class="token template-punctuation string">`</span></span>
      <span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
    <span class="token keyword">if</span> <span class="token punctuation">(</span>amount <span class="token operator">&gt;=</span> totalPriceAmount<span class="token punctuation">)</span> <span class="token punctuation">{</span>
      <span class="token keyword">if</span> <span class="token punctuation">(</span>amount <span class="token operator">-</span> totalPriceAmount <span class="token operator">&gt;</span> <span class="token number">0</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
        console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Here's your </span><span class="token interpolation"><span class="token interpolation-punctuation punctuation">${</span>amount <span class="token operator">-</span> totalPriceAmount<span class="token interpolation-punctuation punctuation">}</span></span><span class="token string"> change</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
      <span class="token punctuation">}</span>
      console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span><span class="token template-string"><span class="token template-punctuation string">`</span><span class="token string">Thanks for your purchase! Hope you come again</span><span class="token template-punctuation string">`</span></span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
      console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>
        <span class="token string">"Sorry, but you don't have enough money to purchase your items"</span>
      <span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
  <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">;</span>
</code></pre>
<p>To test the object, run the code below:</p>
<pre class="language-js" tabindex="0"><code class="language-js">cashRegister<span class="token punctuation">.</span><span class="token function">addItem</span><span class="token punctuation">(</span><span class="token string">"Phone"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
cashRegister<span class="token punctuation">.</span><span class="token function">addItem</span><span class="token punctuation">(</span><span class="token string">"Smart TV"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
console<span class="token punctuation">.</span><span class="token function">log</span><span class="token punctuation">(</span>cashRegister<span class="token punctuation">.</span><span class="token function">calculateTotalPrice</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
cashRegister<span class="token punctuation">.</span><span class="token function">pay</span><span class="token punctuation">(</span><span class="token number">700</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
<p>Output:</p>
<pre class="language-txt" tabindex="0"><code class="language-txt">Adding Phone to your shopping cart
Adding Smart TV to your shopping cart
520
You get a 10% discount and your total price is 468
Here's your 232 change
Thanks for your purchase! Hope you come again
</code></pre>
<!--kg-card-end: markdown--><p>Thanks for reading!</p>

                        

  
                    
