
这里是全屏的显示
<h1>my first webpage</h1>
<p>my first paragraph.</p>
<button onclick="myfunction()"></button>
<script>
function myfunction()
{document.write("....")};
</script>
这里是指定显示
<script>
function myFunction()
{
document.getElementById("demo").innerHTML="My First JavaScript Function";
}
</script>
</head>
<body>
<h1>My Web Page</h1>
<p id="demo">A Paragraph.</p>
<button type="button" onclick="myFunction()"></button>
