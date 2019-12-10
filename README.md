<!DOCTYPE html>
<html>
<head>
<script>
function goBack() {
window.history.back()
}
</script>
<style>

body {
	font-family:Verdana;
	font-size: 16px;
	margin-left:400px;
	margin-right:400px;
	background-color:#ECECEC;
}

h1
{
	font-family:Constantia, "Lucida Bright", "DejaVu Serif", Georgia, serif;
	font-size:40px;
}

hr
{
	border-width:3px;
	border-color:black;
}

div {
	border-style: solid;
	border-color: black;
}

p.centered
{
	text-align:center;
	color:black;
	font-size:14px;
}

a.nav:link, a.nav:visited
{
	display:block;
	font-weight:200px;
	color:#f1f1f1;
	background-color:#005FE0;
	width:31%;
	text-align:center;
	padding:8px;
	text-decoration:none;
	font-family:"Century Gothic";
	font-size:20px;
	float:left;
	border-style:solid;
	border-color:black;
	border-width:3px;
}

a.nav:hover ,a.nav:active
{
	background-color:black;
	color:#f1f1f1;
	font-family:"Franklin Gothic Medium";
}

img.zoom {
	width:500px;
	height:250px;
}


img.zoom:hover 
{
	width:700px;
	height:350px;
}

b.tags
{
	background-color:#ECECEC;
	color:crimson;
}

	button.styled
	{
		background-color: #005FE0;
		color:#f1f1f1;
		width: 200px;
	}
	
	
	button.styled:hover
	{
		background-color:black;
	    color:#f1f1f1;
		width: 200px;
	}
	
		button.styled
	{
		background-color: #005FE0;
		color:#f1f1f1;
		width: 200px;
		height: 30px;
	}
	
	
	button.styled:hover
	{
		background-color:black;
	    color:#f1f1f1;
		width: 200px;
	}
</style>
</head>
<body>

<center>
<h1>How To Program In HTML?</h1>
</center>
    
<center>
<hr>
<ul><a class="nav" href="1 Homepage.html">Home</a></ul>
<ul><a class="nav" href="2 Tutorials Page.html">Tutorials</a></ul>
<ul><a class="nav" href="3 Basic HTML Tags.html">Basic HTML Tags List</a></ul>
</center>
<br>
<br>
<br>

<hr>
	<button class="styled" onclick="goBack()">Go Back</button>

<p>Programming is a good way to train your brain. It is helpful because it makes your brain think. Learning programming is becoming a necessity and it can help you land a good job in the future.</p>
<p>The HTML language stands for Hypertext Markup Language, and it gives a foundation to your website. HTML is widely used to create professional looking websites.</p>
<p>HTML describes the structure and design of a Web page. HTML consists of a series of elements. HTML elements tell the browser how to display the content. HTML elements are represented by tags. Tags display different sections of a website. Browsers do not display the HTML tags, but use them to style the content of the web page.</p>
<h2><b>Introduction</b></h2>
<p>The first tag in a HTML line of code is called the opening tag and the second tag is often referred to as the closing tag. The closing tag is just the normal tag with a <b>forward slash (/)</b> in it.</p>

For Example:<p>The opening tag for creating a paragraph is <b class="tags">&lt;p&gt;</b> and it's closing tag is <b class="tags">&lt;/p&gt;</b>.</p>

<h2>Things You Must Do:</h2>

<p> <strong>ALWAYS</strong> start your HTML programming page with the <b class="tags"> &lt;DOCTYPE html&gt; </b> declaration. This determines what type of document you are using. This declaration helps browsers display you webpage correctly. This command should also only appear once through your code, and it should always be located at the very top.</p>
    
 <p>You should follow this up with a <b class="tags">&lt;html&gt;</b>, and a <b class="tags">&lt;head&gt;</b> command only if you want to style your webpage.</p>
   

<center>

<img class="zoom" src="Screenshot.jpg" alt="!DOCTYPE html">

</center>

<p class="centered"> As you can see above, I started the page with the <b class="tags"> &lt;DOCTYPE html&gt; </b> command.</p>

<h4>How to Execute HTML Programs</h4>

<p>You can use several programs to run or code in HTML. One of the most popular ones is Adobe Dreamweaver, it is not free, but there are alternatives. You can use the built in NotePad application on many Windows OS (operating software) computers. You just type in the code and save it as an HTML file. Then click View in Browser. That should give you a preview of what your have done so far.</p>

<hr>

</body>
</html>

