NOTE: This project was <a href="https://gist.github.com/webuxr/3b44c52752c07a3e6993b3fc847b29f0">forked</a> from <a
href="https://gist.github.com/hugolpz/8075193">Hugolpz GitHub Gist</a>.

<b>Handlebars.js</b> is a convenient, easy to learn JS templating system. 
In this page, we will cover the basics of Handlebars.js.

<h3>What is Handlebars.js ?</h3>
<a href="https://github.com/janl/mustache.js">Mustache.js</a> HTML templates system have been designed to stays extremly simple, on purpose restricted to structure only (logic-less
templating). As such, it excludes logical operators (IF) and alikes.<br /> 

<a href="http://handlebarsjs.com">Handlebars.js</a> HTML templates are based on Mustache.js, so you can start little and simple. Handlebars.js also have logical and advanced
operators so you can later build more complex and conditional stuffs. In this 2nd logic-full level, the HTML-CSS designer of the template will need some basic coding concepts, such
<code>FOR LOOPS</code>, <code>IF</code> (conditional), and few others fundamentals. The <a href="http://handlebarsjs.com">documentations</a> will there be about 3 A4 pages long. 

<h3>Why use JS templating ?</h3>
<img src="8075193/raw/emails.jpg" width="175px;" align="right"></img>
<a href="https://en.wikipedia.org/wiki/JavaScript_templating">JS templating systems</a> are at the core of recent web developpement simplifications. Limited by the smallest
potential mobile devices of visitors/users/customers and requiring more simplicity, recent cross platforms websites and webapps typically use the design method of <b>stacking</b>.
Structurally identical basic elements (usually <<code>div</code>>s) are stacked vertically under each other, each with custom contents from its data source : a local .json file, a
JS <code>localStorage</code> variable with json data, online API's json output, etc.<br /> Emails services such google are a good example of a stable frame with data driven
stacking for the main/central/dynamic area.<br /> 

<b>Handlebars.js</b> {{syntax}} simplify the design of HTML structure and CSS style to the design of one single example element : the template. Yet, Handlebars.js keeps the
possibility of more complex schemes, this easiness to learn with scalability make <b>Handlebars.js</b> a JS templating of choice for fast and clean developements. 

<h3>Project tree</h3>
For self use and the community, this gist contains an handy :<br />
<li>|-index.html: <b>Minimal HandlebarsJS demo within a minimal HTML5 page</b>,<br />(with external jquery & handlebars)</li>
<li>|-css :</li>
<li>|--style.css : non-critical styles</li>
<li>|-imgs :</li>
<li>|--file1.jpg.css : non-critical images</li>
<li>|--file2.jpg.css : non-critical images</li>
<li>|--file3.jpg.css : non-critical images</li>
<li>|-js :</li>
<li>|--data.json : example of data</li>
<li>|--jquery.js : local copy of jQuery</li>
<li>|--handlebars.js : local copy of Handlebars</li>


<h3>Minimal HTML5/HandlebarsJS file</h3>
See: <code>index.html</code>

<!-- <h3>Minimal HTML5-MustacheJS</h3>
See: <code>index.html</code>
-->
<h3>Minimal JSON: data.json</h3>
See asset: <code>data.json</code> for a concise example.

<h3>Sources</h3>
* <a href="http://iviewsource.com/codingtutorials/introduction-to-javascript-templating-with-mustache-js/">Introduction to JavaScript Templating [video tutorial] with
Mustache.js</a> 
* <a href="http://iviewsource.com/codingtutorials/getting-started-with-javascript-object-notation-json-for-absolute-beginners/">A JSON Tutorial. Getting started with JSON using
JavaScript and jQuery</a> 
* <a href="http://cdnjs.com">CDNjs.com</a>
* <a href="http://www.paulirish.com/2010/the-protocol-relative-url/">The Protocol-relative URL</a>
