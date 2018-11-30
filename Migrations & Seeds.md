---


---

<p>knex migrate:make tableName<br>
exports.up creates db<br>
exports.down drops the db<br>
knex.schema.createtable(‘TableName’, table =&gt; {</p>
<p>})</p>
<p>table.increments().notNullable() - Creates a Primary Key<br>
table.foreign('client_id).references(‘<a href="http://clients.id">clients.id</a>’).onDelete(‘CASCADE’) - Creates a foreign key</p>
<p>knex seed:make seedName - Creates a seed file<br>
knex seed:run -Add the seeds to your selected tables</p>

