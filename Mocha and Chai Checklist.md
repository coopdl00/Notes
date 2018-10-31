---


---

<p>create your directory<br>
run npm init -y //to create package.json<br>
run npm install mocha chai // this installs your node modules and a package-lock.json<br>
run mocha init ./test //to create a mocha initiation that puts them into a test directory<br>
inside the /test index.html file add a script tag underneath the script for mocha.js that relays into the node modules chai file // src ="…/node_modules/chai/chai.js"<br>
create main.js inside of your main directory NOT IN THE TEST DIRECTORY<br>
put a script for the main.js file directly above the script tag for your test.js // src = “…/main.js” or if you created a src directory for your js files src = …/src/main.js<br>
put console logs in both your test.js and your main.js saying where they are from so you can tell which ones are connected<br>
write in your test.js file expect or assert for chai // let expect = chai.expect<br>
or assert syntax<br>
write your tests in the test file and do your TDD :D</p>

