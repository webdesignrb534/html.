<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Review Flashcards</title>
<style>
body {
font-family: Arial, sans-serif;
background: #f0f4f8;
margin: 0;
padding: 20px;
animation: fadeIn 1.5s ease-in;
}

h1 {
text-align: center;
color: #333;
margin-bottom: 40px;
}

.container {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 20px;
max-width: 1000px;
margin: 0 auto;
}

.card {
background: white;
border-radius: 8px;
box-shadow: 0 2px 10px rgba(0,0,0,0.1);
padding: 20px;
cursor: pointer;
position: relative;
transition: transform 0.3s ease;
}

.card:hover {
transform: scale(1.05);
}

.question {
font-weight: bold;
color: #444;
}

.answer {
margin-top: 10px;
opacity: 0;
max-height: 0;
overflow: hidden;
transition: opacity 0.5s ease, max-height 0.5s ease;
}

.card:hover .answer {
opacity: 1;
max-height: 200px;
}

@keyframes fadeIn {
from { opacity: 0; transform: translateY(-20px); }
to { opacity: 1; transform: translateY(0); }
}
</style>
</head>
<body>
<h1>Review Flashcards</h1>
<div class="container">
<div class="card">
<div class="question">What is HTML?</div>
<div class="answer">HTML stands for HyperText Markup Language and is used to create the structure of web pages.</div>
</div>
<div class="card">
<div class="question">What does CSS do?</div>
<div class="answer">CSS (Cascading Style Sheets) is used to style and layout web pages, including colors, fonts, and spacing.</div>
</div>
<div class="card">
<div class="question">What is JavaScript used for?</div>
<div class="answer">JavaScript adds interactivity to web pages, such as buttons, forms, and animations.</div>
</div>
<div class="card">
<div class="question">What is a function in programming?</div>
<div class="answer">A function is a block of code designed to perform a particular task, executed when "called".</div>
</div>
<div class="card">
<div class="question">What does the term 'responsive design' mean?</div>
<div class="answer">Responsive design ensures that web pages look good on all devices and screen sizes.</div>
</div>
<div class="card">
<div class="question">What is GitHub?</div>
<div class="answer">GitHub is a platform for version control and collaboration, allowing developers to manage code changes.</div>
</div>
<div class="card">
<div class="question">What is a CSS transition?</div>
<div class="answer">A CSS transition allows property changes in CSS values to occur smoothly over a specified duration.</div>
</div>
<div class="card">
<div class="question">What is the purpose of the `<div>` tag?</div>
<div class="answer">The `<div>` tag is used as a container for other HTML elements to structure a web page.</div>
</div>
</div>
</body>
</html>
