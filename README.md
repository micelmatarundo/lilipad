<!DOCTYPE html>
<html>
  <head>
    <title>Website for My Crush</title>
  </head>
  <body>
    Hihihi mawww po,this is my suprise for you 
  </body>
</html>
<div>
  <h1>Will you be my Valentine?</h1>
</div>
<button id="yesButton">Yes</button>
<button id="noButton">No</button>
body {
  text-align: center;
}
button {
  padding: 10px 20px;
  margin: 10px;
  cursor: pointer;
}
document.getElementById("yesButton").addEventListener("click", function() {
  alert("I love you alwaysss!");
});
document.getElementById("noButton").addEventListener("click", function() {
  // Generate a random position for the button
  var x = Math.random() * window.innerWidth;
  var y = Math.random() * window.innerHeight;
  this.style.left = x + "px";
  this.style.top = y + "px";
});
