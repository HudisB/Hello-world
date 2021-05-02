<!DOCTYPE html>
<html lang="en">
  <head>
    <title> hair by leah</title>
  <link href="styles/index.css" rel="stylesheet">
  </head>
  <body>
    <h1> HAIR BY LEAH</H1>
    <nav>
    <ul>
<li><a href="#information">INFORMATION</li>
<li><a href="#contact">CONTACT</li>
<li><a href="#images">IMAGES</li>
<li><a href="#prices">PRICES</li>
<li><a href="#references">REFERENCES</li>
<li><a href="#ratings">RATINGS</li>
    </ul>
  </nav>
    <button onclick="revealMessage()">Click me!</button>
	<div id="hiddenMessage" style="display:none">
		<p>You are going on a cruise</p>
		<button id="countDownButton" onclick="countDown()">10</button>
	</div>
    <img src="https://femina.wwmindia.com/content/2019/jan/hairstyles-for-girls-with-long-hair-intricate-braids-6091141911547794075.jpg"></ig src>
 <img src="https://content.latest-hairstyles.com/wp-content/uploads/peekoboo-fishtail-braid-prom-curly-500x625.jpg"></img src>
<img src="https://www.momooze.com/wp-content/uploads/Pretty-and-Fabulous-Flower-Girl-Hairstyles-Perfect-for-Any-Wedding-Day-1.jpg"></img src>
<img src="https://www.closetcouture.com/wp-content/uploads/2018/11/189280818-wedding-hairstyles-.jpg"</img src>
<img src="https://i.pinimg.com/originals/70/8c/a5/708ca52f96e1e5829398b1c878ee371c.jpg"></img src>
<img src="https://i.pinimg.com/originals/57/41/75/5741759b58cb94f765f6d3e7ab374a02.jpg"></img src>
    </BODY>
  </HTML>
  /**
 * index.css
 * - Add any styles you want here!
 */

body {
  background-color: #20F667;
  text-align: center;
  word-spacing: 20px;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
   text-align: center;
  overflow: hidden;
  background-color: #F620AF;
}

li{
  display:inline;
  color: black;

  padding: 5px 5px;
  text-decoration: none;
}
li a:hover {
  background-color: #F620AF;
}

/**
 * index.js
 * - All our useful JS goes here, awesome!
 */

console.log("JavaScript is amazing!");

function revealMessage() {
	document.getElementById("hiddenMessage").style.display = 'block';
}

function countDown() {
	var currentVal = document.getElementById("countDownButton").innerHTML;
	var newVal = 0;
	if (currentVal > 0) {
		newVal = currentVal - 1;
	}

	document.getElementById("countDownButton").innerHTML = newVal;
}
