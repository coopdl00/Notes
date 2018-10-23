---


---

<h2 id="document-object-model">Document Object Model</h2>
<p>What is Tree?<br>
Nested HTML Tags. The DOM is a tree<br>
What is API?<br>
They bridge the gap to many different languages<br>
What is DOM?<br>
DOM is an abstraction or model of the web page you are looking at. It is an API that gives us a way to interact with the elements on a page. W interact with it through the document Object.<br>
Find Elements<br>
Elements are </p><h1>My Title</h1> for example<p></p>
<p>Using document to find the elements<br>
Ex.</p>
<h1>Bears!</h1>
<p>find using this<br>
let headerArray = document.getElementsByTagName(“h1”)</p>
<p>Ex.<br>
<img id="mainpicture" class="blue" src=""></p>
<p>use This<br>
let picture = document.querySelector("#mainpicture")<br>
let picture = document.querySelector(".blue")<br>
Using DOM to manipulate Elements<br>
let bearImg = document.querySelector("#mainpicture")<br>
bearImg.src = “Placeholderimg”<br>
bearImg.classname = “Differentimg”</p>
<p>Change the Style of HTML</p>
<p>title.style.fontFamily = “Arial”<br>
title.style.color = “blue”</p>
<p>Changing Attributes</p>
<p>title.setAttribute(‘name’, ‘Yogi’)<br>
title.removeAttribute(‘name’)</p>
<p>Adding/Removing Classes</p>
<p>elem.classList.remove(‘work’)<br>
elem.classList.add(‘party’)<br>
elem.classList.toggle(‘disco-ball’)<br>
elem.classList.contains(‘boss’)</p>
<p>document.createElement(‘p’) ; Creates an element</p>
<p>To Insert an element<br>
body.appendChild(newimg)</p>
<p>Remove or Replace an Element<br>
.appendChild()<br>
.replaceChild()<br>
.removeChild()</p>

