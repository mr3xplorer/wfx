# WFX Website Effects

Welcome to the **WFX Website Effects** is dedicated to various inspiring and creative website effects, gathered to enhance web design and user experience.

## Effects

| Effect                | Description                                                                                                                                                 | Code Example                                                                                                                                                      |
|-----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Hover Effects**     | Hover effects enhance user interaction by applying visual changes to elements when hovered over with a cursor.                                               | ```css<br>.button {<br>  transition: background-color 0.3s ease;<br>}<br><br>.button:hover {<br>  background-color: #f00;<br>}```                                   |
| **Parallax Scrolling**| Parallax scrolling creates an illusion of depth by making background images move slower than the foreground content.                                         | ```html<br><div class="parallax" style="background-image: url('background.jpg');"></div>```<br>```css<br>.parallax {<br>  height: 500px;<br>  background-attachment: fixed;<br>  background-position: center;<br>  background-repeat: no-repeat;<br>  background-size: cover;<br>}```|
| **Smooth Scrolling**  | Smooth scrolling provides a seamless navigation experience by animating the scrolling between sections.                                                      | ```css<br>html {<br>  scroll-behavior: smooth;<br>}```                                                                                                            |
| **Loading Animations**| Loading animations keep users engaged while content is being loaded, improving the user experience.                                                          | ```html<br><div class="spinner"></div>```<br>```css<br>.spinner {<br>  border: 16px solid #f3f3f3;<br>  border-top: 16px solid #3498db;<br>  border-radius: 50%;<br>  width: 120px;<br>  height: 120px;<br>  animation: spin 2s linear infinite;<br>}<br><br>@keyframes spin {<br>  0% { transform: rotate(0deg); }<br>  100% { transform: rotate(360deg); }<br>}```|
| **Fade-In Effects**   | Fade-in effects make elements gradually appear on the screen, providing a smooth and polished look.                                                           | ```css<br>.fade-in {<br>  opacity: 0;<br>  transition: opacity 1s ease-in;<br>}<br><br>.fade-in.visible {<br>  opacity: 1;<br>}```<br>```javascript<br>document.addEventListener("DOMContentLoaded", function() {<br>  var fadeInElements = document.querySelectorAll('.fade-in');<br>  fadeInElements.forEach(function(element) {<br>    element.classList.add('visible');<br>  });<br>});```|
| **Carousel-Sliders**  | Carousels and sliders allow you to display multiple pieces of content within a single space, enhancing the visual appeal and usability of your website.       | ```html<br><div class="slider"><br>  <div class="slide">Slide 1</div><br>  <div class="slide">Slide 2</div><br>  <div class="slide">Slide 3</div><br></div>```<br>```css<br>.slider {<br>  display: flex;<br>  overflow: hidden;<br>}<br><br>.slide {<br>  min-width: 100%;<br>  transition: transform 0.5s ease-in-out;<br>}```<br>```javascript<br>let currentSlide = 0;<br>const slides = document.querySelectorAll('.slide');<br><br>setInterval(() => {<br>  currentSlide = (currentSlide + 1) % slides.length;<br>  document.querySelector('.slider').style.transform = `translateX(-${currentSlide * 100}%)`;<br>}, 3000);```|

---

**Pen✒️**

- [neon text editor](Funzone-neon)
- [deep dive](https://codepen.io/alexandrevacassin/pen/rNgzOXY)
  
---
Happy coding! 🎨✨



