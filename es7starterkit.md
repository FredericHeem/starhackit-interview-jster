---
title: 'StarHackIt - A Full Stack ES6/ES7 Web Application Starter Kit based on React and Node - Interview with Frederic Heem'
date: 2015-10-XX
headerImage: '/assets/img/starterkit.jpg'
---

I discussed my [React component boilerplate](FIXME) earlier on. It is focused and deals only with the front-end. That said, often you need to have some sort of back-end in place as well. Frederic Heem's [ES7 StarHackIt](http://starhack.it/) is a solution that aims to solve this problem. Read on to learn more.

## Can you tell a bit about yourself?

<p>
  <span class="author">
    <img src="hf.jpg" alt="MrM" class='author' width='100' />
  </span>
</p>

I studied industrial engineering in France but ended up being a software engineer for the last the last 15 years mostly the UK and Italy. Right now, I am working on blockchain and distributed ledger technology in the city of London. During my freetime and when the wind blows, I am hooked on my kitesurf.

## How would you describe StarHackIt to someone who has never heard of it?
*StarHackIt* is a boilerplate of a fullstack web application. The aim is to provide a full development lifecycle code base to quickly create new web application. It is a foundation on which software developers can build web applications on top of it. 

One of the base feature is *authentication*:

* user can register and login with username and password, reset the password via email.
* social login with Facebook, Google, GitHub etc ... 

A fine grained *authorization* system based on groups, permissions and resources is also provided. This allows to create users belonging to groups with differrent access rights to the API. A simple example is to set restricted acces to users belonging the to *Admin* group. 

This starter kit is written in Javascript *ES6*/*ES7*, it is composed of a frontend based on *React*/*Reflux*, a *Node.js* backend, the data is backed by *SQL* thanks to the *Sequelize ORM*, automatic deployment is done with *Ansible*. The code is built with *Gulp*, analyzed by *ESlint*, tested with *Mocha*, covered by *Istanbul*.


## Why did you develop StarHackIt?

Almost if not all of the Javascript boilerplates are not really full-stack, either they focussed on the frontend or on the backend.

The data is almost always stored in non relational *NoSQL* database like *mongodb* or in the cloud with *firebase*. However, most of the applications rely on relational data and plain old relation databases like *Postresql* or *MySql* are better suited.

<p>
  <span class="author">
    <img src="nosql.jpg" alt="nosql" />
  </span>
</p>

The **MEAN stack** is quite popular, it's composed of *MongoDB*, *Express*, *Angular* and *Node*. Instead *StarHackIt* is a **SERNA stack**: *SQL*, *Express*, *React*, *Node* and *Ansible*.

The Ruby devs have ruby on rails but the Javacript devs don't have node on rails (yet). This project is a little step towards the direction of a productive javascript web framework.

Image that you have to attend a hackaton to create a useful app in a weekend, is there any time to lose creating from scratch an application with login and password ? 

## What kind of challenges have you experienced while developing it?
The Javascript ecosystem is vibrant with a record number of packages that have overtaken any other languages, see [modulecount](http://www.modulecounts.com/) for the facts.

<p>
  <span class="author">
    <img src="modulecounts.png" alt="modulecounts" class='author' />
  </span>
</p>

The challenge is mostly about making choice between these huge numbers of packages to build upon:

* React/Angular/Angular2/Ember/Backbone
* Reflux/Flux/Redux/Alt
* Bootstrap/Material/Foundation
* Eslint/Jscs/Jshint
* Stylus/Saas/Less/CSS
* Express/Koa/Hapi/Strongloop/Sails/Meteor
* SQL/NoSql
* Sequelize/Bookshelf
* Webpack/Browserify/RequiresJs
* Gulp/Grunt
* Ansible/Chef/Puppet
* Mocha/QUnit

It's all about selecting the best tools at a given time and integrating them. Over time, new libraries will emerge, other libraries will be unmaintained. Keeping the code up to date with the new version requires some substantial maintenance.

<p>
  <span class="author">
    <img src="choosepillsmatrix.jpg" alt="modulecounts" class='author' />
  </span>
</p>

Writing code in *ES6* and *ES7* adds another layer of complexity on the build system since files needs to be transpiled to plain old javascript. This also makes setting code coverage and testing trickier. It's definitely worth it however. The most amazing feature with *ES7* is **async/await**, forget about callback and Promises, async/await is an enlightenment and the way to go, it makes writing asynchronous code similar as writing synchronous code, it significantly changes the way javascript is written, especially on the node side.


## What next?
Next is to improve the documentation to explain the various part of the stack, write a tutorial on how to create a fullstack TODO app. Then a native mobile app with react-native is definitely on the road map. An admin interface to manage users and other aspects of the app would be also very useful.


## What does the future look like for React and front-end in general? Can you see any particular trends?
The future of React lies in the various flux implementations that are evolving very quickly, React is only a part of the equation for building an application. The React community are growing at fast pace, for instance, the React Meetup in London is fully booked only after 20 min upon publication of the event. The frontend development and software in general have a bright and sustainable future, there is no shortage of software development job in sight.


## Who should I interview next?
What about an interview of Juho Vepsäläinen ? The man behind [jster.net](http://jster.net/)


## Conclusion

JV: I'll fill this. Thanks etc. :)

If you want to look into StarHackIt, consider the following resources:

* [starhack.it](http://starhack.it)
* [source code on GitHub](https://github.com/FredericHeem/starhackit)
