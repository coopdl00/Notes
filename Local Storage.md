---


---

<h2 id="local-storage">Local Storage</h2>
<p>It allows you to store information about a user, for later use.</p>
<p>Methods:</p>
<ul>
<li>
<p>setItem:  Set a key/value pair in local storage. Keys and values must both be strings ex. localstorage.setItem(‘name’, ‘Danny’)</p>
</li>
<li>
<p>getItem: Get the value stored at a key in local storage. Will always return a string or null ex. localstorage.getItem(‘name’)</p>
</li>
<li>
<p>removeItem: Remove a key/value pair from local storage. ex. localstorage.removeItem(‘name’)</p>
</li>
<li>
<p>clear: Completely empty the local storage ex. localstorage.clear()</p>
</li>
</ul>
<p>ONLY STRINGS<br>
JSON.stringify(variable) makes an object into a string<br>
JSON.parse(localStorage.getItem(‘variable’): makes a string into an object</p>
<p>First get the Item from local Storage<br>
then push to that array<br>
setItem back into local storage</p>

