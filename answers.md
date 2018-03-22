PART 1

Question 1:

var image = document.getElementsByClassName("profile-image")[0]

image
<img src=​"images/​self-portrait-grassbg.jpg" alt=​"Self Portrait" title=​"Self Portrait" class=​"profile-image">​
image.src
"http://bitmakerlabs.github.io/panda-the-bear-js/images/self-portrait-grassbg.jpg"
image.src = "https://placebear.com/200/300"
"https://placebear.com/200/300"

-----------------------------------------------------------

Question 2:

var title = document.querySelector('h1');
title
<h1 class=​"highlight">​Panda The Bear​</h1>​
title.innerText = "Debbie Rosenfeld"


-----------------------------------------

Question 3:

var employmenttitle = document.querySelector('#employment .info-title');
employmenttitle
<h3 class=​"info-title">​…​</h3>​
employmenttitle.innerText = "My Jobs";


-----------------------------------------------------

Question 4:
var bodycolor = document.querySelector('body')
bodycolor.style.backgroundColor = 'grey';


-------------------------------------------------------

Question 5:

var highlight = document.getElementsByClassName("highlight");

for(var i = 0; i < highlight.length; i++){ highlight[i].style.backgroundColor = "pink"; }
"pink"

------------------------------------------------------------

Question 6:

var bodyfont = document.querySelector('h1');

bodyfont.style.fontFamily = 'monospace';


------------------------------------------------------------

Question 7:

var circleicon = document.getElementsByClassName('action-icon-bg');
circleicon

for(var i = 0; i < circleicon.length; i++){ circleicon[i].style.backgroundColor = "blue"; }


--------------------------------------------------------

Question 8:

contactname = "Identify yourself"
var contactname = document.querySelector('#name').placeholder = "Identify yourself";

----------------------------------------------------------

Question 9:

var msgfield = document.querySelector('#message').placeholder = "state your business";

---------------------------------------------------------

Question 10:

var namevalueattr = document.querySelector('#name').value = "your nemesis";


---------------------------------------------------------

Question 11:

var namevalueattr = document.querySelector('#email').value = "koalathebear@gmail.com";

----------------------------------------------------------

Question 12:

var submitbutton = document.querySelector('#submit').value = "En garde!";

-------------------------------------------------------------

Question 13:

submitbutton.disabled = true;


-------------------------------------------------------------

Question 14:
var sidebar = document.getElementsByClassName('bio-info-value');


for(var i = 0; i < sidebar.length; i++){ sidebar[i].remove() };

-----------------------------------------------------------

PART 2

Question 1:
