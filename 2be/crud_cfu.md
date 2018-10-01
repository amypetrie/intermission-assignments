1. Define CRUD.

CRUD stands for Create, Read, Update, Delete, and is a model that a relational
database application should be able to execute. SQL and HTTP can map to each
operation in CRUD.

2. Why do we use set method_override: true?

We do this so that we can detect the the `_method` param passed in by a browser
from a form to support an HTTP non-standard method like PUT and DELETE.

3. Explain the difference between value and name in this line: `<input type='text' name='task[title]' value="<%= @task.title %>"/>.`

This is a name/value pair.

4. What are params? Where do they come from?

Params are a hash available in route blocks that automatically include relevant data from the HTTP request (URL matches, data sent in HTML forms, etc.).

5. Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?

We need separate routes for separate functions because HTTP requests need to be routed to the piece
of code that handles that specific request and response.
