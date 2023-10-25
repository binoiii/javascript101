# Introduction to JavaScript

## Brief Overview of Javascript

Javascript is used to make websites interactive.
Example:
Paste the code below in the [playground](https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_lightbulb) to simulate.

```<!DOCTYPE html>
<html>

<style>
 button {
     border: 1px solid green;
        border-radius: 10px;
        padding: 20px;
        background-color: #ffffff;
        color: green;
    }

</style>

<body>

<h2>What Can JavaScript Do?</h2>

<p>JavaScript can change HTML attribute values.</p>

<p>In this case JavaScript changes the value of the src (source) attribute of an image.</p>


<button onclick="turnOn()">Turn on the light</button>

<img id="myImage" src="pic_bulboff.gif" style="width:100px">

<button onclick="turnOff()">Turn off the light</button>

</body>

<script>

function turnOn() {
  document.getElementById('myImage').src='pic_bulbon.gif'
}

function turnOff() {
  document.getElementById('myImage').src='pic_bulboff.gif'
}

</script>

</html>
```

## Importance of JavaScript in Web Development
