---
layout: post
title:  "Certifed FERN Fanboy"
date:   2022-06-13 00:14:08 +1200
categories: jekyll update
---

The FERN tech stack has easily become my top recommendation for any small-medium sized webapp, with just a bit of JavaScript and $0 devs can create and host a complete modern SPA. A tech stack describes the set of tools involved in building or running a project. In the case of a webapp this typically consists of frontend & backend libraries paired with some kind of database. 

![FERN](/assets/FERN_stack.png)

FERN stands for [Firebase], [Express.js], [React.js] and [Node.js]. Firebase is a Google owned development platform which provides access to Cloud Firestore, our database in this tech stack. Firebase is the real magic of this stack in my opinion, more on their remarkable free tier below. Express.js is a backend framework powered by Node.js and React.js is our frontend framework (technically a library but w/e).

## Why Firebase?

Firebase is great at simplifying the otherwise complex. Their NoSQL database solution follows this mantra to a tee. NoSQL is quite intuitive and the finer details are unlikely to bite you on small projects. MongoDB is the obvious competitor, but Firebase's free tier provides so much more.

## Why Express?

The beauty of opting for Express in this tech stack is that your whole stack uses the same programming language: JavaScript. Most small projects are written by a single dev, meaning you'll often be switching between frontend and backend development regularly. Reducing the load on your brain when [context switching] means more development, less deleting `True` when you realise you wanted `true`. [Koa] is another JavaScript framework from the people behind Express and could honestly be a better choice here, but it ruins the pretty acronym :^).

Python's Django or Flask will also do nicely. Ruby on Rails if you're old. Spring Boot if you hate fun.

## Why React?

While I'd argue Firebase or Express for hours, I'm pretty open to plugging almost any frontend framework in here. Let's take a look at three of the most common: as the most popular frontend library, React.js is the natural choice in my opinion. With heaps of online resources, resuable components and widespread adoption, there's a lot to love. Vue.js is a great option to pick up quickly, it's the framework of choice in UC Software Engineering courses. I'd warn new devs against Angular, the difficult learning curve won't reward you with much noticeable advantage for small projects.

Here's some results from the latest State of JS [survey]:

![results](/assets/frontends.png)

## Why Not?

The best way to tell if you're going to enjoy working with this tech stack is to give it a go, and that's the beauty of it! Giving it a go is as easy as possible. You can get a minimum viable product up and running in a much shorter time than other similar tech stacks. 

Check out the [webapp] I created for a discord server if you're looking for inspiration.

First image is from [this article]

See how I made the headings spell FERN?

[context switching]: https://www.linkedin.com/pulse/context-switching-developers-paul-graham
[Firebase]: https://firebase.google.com/
[Express.js]: https://expressjs.com/
[React.js]: https://reactjs.org/
[Node.js]: https://nodejs.org
[Koa]: https://koajs.com/
[webapp]: https://github.com/georgeaholden/slim-jim-website
[survey]: https://2021.stateofjs.com/en-US/libraries/front-end-frameworks/#front_end_frameworks_experience_ranking
[this article]: https://javascript.plainenglish.io/getting-started-with-the-fern-stack-firebase-express-react-node-js-2a97b93bd920
