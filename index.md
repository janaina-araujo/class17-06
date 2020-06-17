<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Statements</h2>

<p>JavaScript code blocks are written between { and }</p>

<button type="button" onclick="myFunction()">Click Me!</button>
<button type="button" onclick="myFunction1()">Click another Me!</button>
<button type="button" onclick="myFunction2()">Click me to say yes or no!</button>
<button type="button" onclick="myFunction2()">Another button 4th</button>
<p id="demo1"></p>
<p id="demo2"></p>
<p id="demo3"></p>
<p id="demo4"></p>
<p id="demo5"></p>

<script>
function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  document.getElementById("demo2").innerHTML = "How are you?";
  document.getElementById("demo3").innerHTML = "Are you Good?";
}
function myFunction1() {
  document.getElementById("demo4").innerHTML = "Demo4 Says yes!";

}
function myFunction2() {
  document.getElementById("demo4").innerHTML = "Demo4 Says no!";

}
</script>

</body>
</html>
