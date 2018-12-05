---


---

<h1 id="serverside-validation">ServerSide Validation</h1>
<p>We can implement validation with forms on the front end and inside your database and routes</p>
<p>RULE #1<br>
don’t trust the user</p>
<p>Redundancy is good for protection against malicious users</p>
<p>Joi: it’s a middleware that does the actual validation</p>
<p>Express-Validation: It’s how you use Joi inside of a route</p>
<p>Use must use a catch all when using Joi and Express - Validation<br>
Custom validation using next()<br>
router.use((err, req, res, next) =&gt; {<br>
res.status(err.status).send(err)<br>
}</p>

