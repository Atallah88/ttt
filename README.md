# ttt
<!DOCTYPE html>
<html>
<head>
<style> 
div{
width: 100px;
height: 100px;
background: black;
transition: width 1s;}
#div1 {transition-timing-function: linear;}
#div2 {transition-timing-function: ease;}
#div3 {transition-timing-function: ease-in;}
#div4 {transition-timing-function: ease-out;}
#div5 {transition-timing-function: ease-in-out;}
div:hover {
width: 300px;}
</head>
<body>
<div id="div1"></div><br>
<div id="div2">ease</div><br>
<div id="div3">ease-in</div><br>
<div id="div4">ease-out</div><br>
<div id="div5">ease-in-out</div><br>
</body>
</html>
