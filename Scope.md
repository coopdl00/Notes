---


---

<p>Global Scope<br>
var scope = ‘global’</p>
<p>function testscope() {<br>
console.log(scope)<br>
}</p>
<p>testscope()<br>
It returns ‘global’<br>
Functional Scope<br>
var scope =</p>
<p>Shadowing</p>
<p>var scope = 1<br>
function testscope() {<br>
var scope = 2<br>
console.log(scope)<br>
}</p>
<h2 id="hoisting">Hoisting</h2>
<p>It creates all the variables on the page and on the second pass it assigns the values</p>

