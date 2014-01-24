# Middleman + Ember + Bower Template

A Middleman template for getting started with Ember and Bower

## Why?

When I first started out using Middleman with Ember, it took me a little while to get everything together, hunting down the right gems to get the templates to compile, setting up Sprockets to use Bower assets, etc.  Instead of doing all that legwork again, I decided to make a starter package that provides a good jumping-off place if you're looking to use the same setup (which I highly recommend).

## Structure

```
source/
    fonts/
    images/
    javascripts/
        controllers/
        models/
        routes/
            router.js
        templates/
            application.hbs.erb
        views/
        application.js
        main.js
    layouts/
    stylesheets/
    index.html.erb
```

## Installation

```bash
cd ~/.middleman
mkdir ember-bower
cd ember-bower
git clone git@github.com:alexlafroscia/middleman-ember-starter.git .
```

**Note:** Remember the dot at the end of the `git clone` command!

## Usage

### Creating a new project

```bash
middleman init my_project --template=ember-bower
```

This will create a fresh project for you, based on this template!

### Set Up

As a quick overview of the commands involved in getting things installed

#### Installing Dependencies

```bash
bundle install
bower install
```

#### Running the Server

```bash
middleman server
```
Starts server at `localhost:4567`

or 

```bash
middleman -p 3000
```
Starts server at `localhost:3000`

***

Questions/Comments/Suggestions? Come find me on [Twitter](http://www.twitter.com/alexlafroscia) or send me an email!
