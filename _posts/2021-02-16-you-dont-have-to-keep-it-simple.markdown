---
layout: post
title:  "You don't have to keep it simple"
date:   2021-02-16 16:25:32 -0300
categories: software engineering
---
The answer to all questions is "**depends**".

Should I choose tool "x" or "y"? It depends...

Should I apply MVC or Clean Architecture? It depends...

Should it be simple or complex? It depends...

## A simple excercise...

> We need a service that must register a user with name and email parameters. After a user is registered, the service must send a welcome email.

The sentence above is everything the service will do. That's it.

Now a question for you: would you apply Clean Architecture when implementing a software like that, using entitites, use cases, adapters and all the CA stuff?

No? Why?

"Because it's a overengineering practice!", you may answer.

But what if we need to teach about Clean Architecture for the first time in a easy way? Should you use complex requirements to implement CA? I think in this case, with the first time teaching in mind, the answer is **not**.

When discussing a software engineering decision, we need first understand the motivation behind of that decision.

KISS or YAGNI are not end goals unto itself. Clean Architecture, MVC or everything written in the `main` function are just decisions inside of a context.

Nothing in software engineering is made of diamonds.
