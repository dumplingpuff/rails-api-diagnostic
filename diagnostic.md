# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
"The backend allows to have data store, or persistence which is data stored
over time."
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
"The controller uses the model to fetch data."
```

Which layer in the MVC pattern communicates with the model?

```bash
"The model only communicates to the controller"
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
"Views is not used because we are working with single page applications. From
what I understand views is used when there are multiple pages and is needed
to render a different view of the html based on the request."
```

What does C.R.U.D stand for?

```bash
"Create, Read, Update, Destroy"
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
"I feel like I may answer this wrong, but the routes file houses the proper
controller action.  The routes determine which
controller and action, but the controller houses the actual C.R.U.D. actions."
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
"The request would first hit the routes file. The routes would say 'person controller
show person 1'.  The Person controller looks at it goes bother model to get person
1 data, model gives it to controller and the controller returns it to the server."
```

What is the command to generate a new rails-api app?

```bash
"rails-api app -T --database=postgresql
in our class case we skipped setting up a database."
```

What is the command to start an instance of a rails server?

```bash
"bundle exec rails s or rails s"
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
"rake db:drop
rake db:create
rake db:migrate"
```

What is the command to scaffold a pet with a name and an age?

```bash
"Ran out of time"
```

List two advantages of using serializers? (2 bullet points)

```bash
"Ran out of time"
```
