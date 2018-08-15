---
layout: portfoliopost
comments: true
title: Microsoft AR/VR Hackathon
subtitle: "Playing with emojis in a 360-photo"
date: 2017-04-28
tags: [Post]
author: "Lisa Jiamsirioungkul"
header-img: /img/fundo_main.png
modal-id: 2
thumbnail: /img/portfolio/vr-hackathon/coverimg.png
description: Drag & Drop was created to play with emoji within a 360 space. 
---
## Microsoft VR Hackathon

Microsoft AR/VR Hackathon was held on April 28-30, 2017 at Mircosoft, Redmond campus. The theme of the hackathon was "putting objects in a space" using virtual reality, augumented reality, or 360 imaging.

Drag & Drop was developed in a 48 hour period of the hackathon. My group used Google DayDream to play with emoji in a 360 sphere. 

I worked as a VR Interaction Designer and Product Manager on the project. My work included grabbing 360 photos and videos, formatting and scaling the images into Unity, and understanding the image coordinates and bitmapping. Formatting and scaling the file was my stetch work since it was my first time using the 360 imaging device. Formatting the image from a panorama (2D format) into a spherial (3D format) was the most challenging part of the project since there were few 360 stitching software. 

The other part of the project was to make the presentation. Something I wanted to show about the our project was how it would impact the real world. Although clicking and pasting emojis into a 360 image may sound simple in application, it could be used in a variety of ways. For example, our application could be used in interior design with invisioning a couch placement in a room without lifting anything. It could also be used medically in imaging of plastic surgery. I wanted to show off the endless possbilities of our project.

At the end of the hackathon, Drag & Drop won first place! I was really surprised since there were many other talented projects in the room.  


#### Here are my three takeaways from the VR/AR hackathon:


##### 1. Everyone is new to something

Virtual reality (VR) and augumented reality (AR) is emerging to become a new segment in the tech world. To many people in attendance, this was their first VR/AR time learning about controllers, world building, and head mounts.

##### 2. Build Your MVP (Minimum Viable Product)
In our process building phase, we had many ideas tossed. Some were ideal. Some were unreachable within the hackathon. There was a 48 hour time limit on this hackathon. My teammates were from out of town and were only avaliable during the hours of the hall being open. Coming as a group and finding what was most viable for us to build the product was neccessary at the beginning. It helped us save time and know our goal to finishing the product.

##### 3. There's No One Way

As many of us presented our work, it became apparents how one theme can create many ways of reaching the theme. Many attendees used Microsoft Hololens as project headmount. Some teams had the amazing idea to use Amazon Alexa to call functions within their head mount. There were no "one way" of making a product at the event. 

### ROLE
VR Interaction Designer and Product Manager

### DATE OF EVENT
April 28-30, 2017

### PROJECT DELIVERABLE

<div class="w3-content w3-display-container" style="text-align: center;">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page1.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page2.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page3.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page4.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page5.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page6.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page7.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page8.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page9.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page10.png" style="width=718px">
  <img class="mySlides" src="/img/portfolio/vr-hackathon/page11.png" style="width=718px">

  <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
  <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>



### RESOURCES

<a href="https://github.com/googlevr/gvr-android-sdk">Google VR SDK Sample Github</a>

<a href="https://developers.google.com/vr/daydream/overview">Google Daydream SDK</a>

