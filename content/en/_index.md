---
description: "The wedding of Nick Gerakines and Mattie Carter"
cascade:
  featured_image: 'IMG_3335.jpeg'
---

The big day is June 24th, 2023. Join us in Dayton, Ohio.

<p id="theDay">... </p>

<script>
var countDownDate = new Date("Jun 24, 2023 17:00:000").getTime();
var x = setInterval(function() {
  var now = new Date().getTime();
  var distance = countDownDate - now;
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
  document.getElementById("theDay").innerHTML = "Just " + days + " days, " + hours + " hours, and " + minutes + " minutes away!";
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("theDay").innerHTML = "EXPIRED";
  }
}, 1000);
</script>
