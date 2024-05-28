---
title: Introduction to Ruby on Rails
category: Jekyll
layout: post
---

# What is Ruby on Rails?

Ruby on Rails is a framework to develop web applications.

* Ruby is a programming language
* Rails is the name of the framework


# Why use Ruby on Rails instead of Python, JavaScript, etc?

* Convention over configuration
* Starts with helpful defaults, but everything is modular!
* Uses the Model-View-Controller (MVC) Architecture

# What is the Model-View-Controller architecture?

![MVC Diagram](assets/images/MVC.png)

# A Rails demo application

After installing all necessary dependencies, we created the first demo app.

Learning targets:

* MVC Architecture
* Controllers
* Controller Actions
* Routes
* Rails Action Helpers

At the command prompt:

```sh
$ rails new demo
```

This will start an installation of all the dependencies (from now on called "gems").

Next we created a `Controller` with two actions: `say` and 
`goodbye` using this command:

```sh
$ rails generate controller Say hello goodbye
```

These files will be created for us:

* `app/controllers/say_controller.rb`
*  `app/views/hello.html.erb` 
* `app/views/goodbye.html.erb`

