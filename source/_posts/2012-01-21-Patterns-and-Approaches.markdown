---
layout: page
single: true
---

I am member of [Exercise.com](https://www.exercise.com/) team. We are building our awesome web-application using cutting-edge technologies such as Symfony2, Doctirne2, Twig etc.
<!-- more -->
This is fortunate use latest trends in you sphere (PHP for me). As said my old friend Thibault Duplessis, also known as [@ornicar](https://twitter.com/ornicar): "We are code warriors." This libs provide deadly simple and clear API to use them, but sometimes I feel like a user in our complex application. I exactly know how to do this or that feature, but not always know how it works under the hood.

Doctrine2.

As doc said it based on several patterns: DataMapper, UnitOfWork, Repository.
Time by time I have reviewed doctrine code to understand some logic or flow, but it's only occasionally.
Before dive deeper into doctine, and probably send any PR or write extension, you should at least understand base patterns on which it based.

I have asked bible of patterns [GoF -- Design Patterns](http://www.amazon.com/dp/0201633612/), but not luck, I have found nothing similar to DataMapper, UnitOfWork or Repository.

In few minutes I have found next awesome book, that I want to advice to you, it's [Patterns of Enterprise Application Architecture](http://www.amazon.com/dp/0321127420/) by Martin Fowler. It describes, as far as I got, not patterns but, probably, approaches. Despite title Patterns of Enterprise blah-blah... you can, and I highly recommend to you, use described approaches in you daily work.

There is list of approaches described in book (alphabetical order).
I have marked doctrine related approaches via bold:

* Active Record
* Application Controller
* Association Table Mapping
* Class Table Inheritance
* Client Session State
* Coarse-Grained Lock
* Concrete Table Inheritance
* **Data Mapper**
* Data Transfer Object
* Database Session State
* Dependent Mapping
* **Domain Model**
* Embedded Value
* Foreign Key Mapping
* Front Controller
* Gateway
* Identity Field
* **Identity Map**
* Implicit Lock
* Inheritance Mappers
* Layer Supertype
* Lazy Load
* Mapper
* Metadata Mapping
* Model View Controller
* Money
* Optimistic Offline Lock
* Page Controller
* Pessimistic Offline Lock
* Plugin
* Query Object
* Record Set
* Registry
* Remote Facade
* **Repository**
* Row Data Gateway
* Separated Interface
* Serialized LOB
* Server Session State
* Service Layer
* Service Stub
* Single Table Inheritance
* Special Case
* Table Data Gateway
* Table Module
* Template View
* Transaction Script
* Transform View
* Two Step View
* **Unit of Work**
* Value Object

Good luck with patterns!
