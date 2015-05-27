---
layout: post
title: Express MVC Structure Part I
published: true
---

In this post I will tell you my experiences with [Node.js][2] and [Express.js][1].
[Express][1] and [Node][2] allow you to structure your application in various ways,
so I was trying to find the best structure that fits my needs.
While working on an app I tried different things until I used [Sails.js][3].
The structure of [Sails][3] gave me the idea to implement it using [Express][1].

This will be a Tutorial on how I structure my [Node][2] applications. At first I will
show you the what you need and how the app will look like.

So what's necessary... At first I assume that you have Node and npm installed.
I use [Grunt][4] and [CoffeeScript][5] for my apps. With the help of [CoffeeScript][5]
allows the app will llok more structured. To install all these just run the following commands:

{% highlight bash %}
sudo npm install -g grunt-cli
sudo npm install -g express
sudo npm install -g express-generator
sudo npm install -g coffee-script
{% endhighlight %}

The directories we will need are the following:
{% highlight bash %}
assets
  stylesheets
  javascripts
config
controllers
models
policies
routes
views
{% endhighlight %}

The next steps on creating the whole application will be demonstrated in the next part.

[1]: http://expressjs.com/
[2]: https://nodejs.org/
[3]: http://sailsjs.org/#!/
[4]: http://gruntjs.com/
[5]: http://coffeescript.org/