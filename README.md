# bsless-app

## The heck is this

An attempt to define a generic, detailed and correct model specification for simple applications.

## Motivation

I'd just want to stop writing non-sensical code for the nth CRUD application, dealing with low-level concerns, trying to keep pace with the latest technology, reinventing the wheel everytime write actual code.
Let's be honest, this is an old and known problem that can be easily (I hope) defined formally. 
What if you could write an app definition and then use a machine to build a fully working automatically validated solution? 
I think that code must be avoided at all costs and I also think that enterprise programmers are over exposed to low level technical noise which makes them sad and expensive. 

## Strategy

* Create a single model specification that can represent an application. This model uses concepts from other contexts (like DDD) that are well known by the community and have strong semantic significance.
* Write application definitions using that model.
* Persist application definitions and use a backend to consume/process them.

Backends are sort-off out of scope of this project. Backends are programs that interpret an application definition and provide an actual application ready to be used.
