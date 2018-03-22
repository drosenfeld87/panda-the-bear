Question 1:

var image = document.getElementsByClassName("profile-image")[0]
undefined
image
<img src=​"images/​self-portrait-grassbg.jpg" alt=​"Self Portrait" title=​"Self Portrait" class=​"profile-image">​
image.src
"http://bitmakerlabs.github.io/panda-the-bear-js/images/self-portrait-grassbg.jpg"
image.src = "https://placebear.com/200/300"
"https://placebear.com/200/300"

-----------------------------------------------------------

Question 2:

var title = document.querySelector('h1');
undefined
title
<h1 class=​"highlight">​Panda The Bear​</h1>​
title.innerText = "Debbie Rosenfeld"
"Debbie Rosenfeld"

-----------------------------------------

Question 3:

var employmenttitle = document.querySelector('#employment .info-title');
undefined
employmenttitle
<h3 class=​"info-title">​…​</h3>​
employmenttitle.innerText = "My Jobs";
"My Jobs"

-----------------------------------------------------

Question 4:
var bodycolor = document.querySelector('body')
undefined
bodycolor.style.backgroundColor = 'grey';
"grey"

-------------------------------------------------------

Question 5:

var highlight = document.getElementsByClassName("highlight");
undefined
highlight
HTMLCollection(8) [aside.highlight, h1.highlight, div#sleep.bar-filled.highlight, div#eat.bar-filled.highlight, div#time-travel.bar-filled.highlight, div#cry.bar-filled.highlight, h2.highlight, h2.highlight, sleep: div#sleep.bar-filled.highlight, eat: div#eat.bar-filled.highlight, time-travel: div#time-travel.bar-filled.highlight, cry: div#cry.bar-filled.highlight]

for(var i = 0; i < highlight.length; i++){ highlight[i].style.backgroundColor = "pink"; }
"pink"

------------------------------------------------------------

Question 6:

var bodyfont = document.querySelector('h1');
undefined
bodyfont
<h1 class=​"highlight" style=​"background-color:​ pink;​">​Debbie Rosenfeld​</h1>​
bodyfont.style.fontFamily = 'monospace';
"monospace"

------------------------------------------------------------

Question 7:

var circleicon = document.getElementsByClassName('action-icon-bg');
undefined
circleicon
HTMLCollection(2) [a.action-icon-bg, a.action-icon-bg]0: a.action-icon-bg1: a.action-icon-bglength: 2__proto__: HTMLCollection
for(var i = 0; i < circleicon.length; i++){ circleicon[i].style.backgroundColor = "blue"; }
"blue"
"blue"

--------------------------------------------------------

Question 8:

contactname = "Identify yourself"
var contactname = document.querySelector('#name').placeholder = "Identify yourself";
