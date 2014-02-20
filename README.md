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
        templates/
            application.hbs.erb
        views/
        application.js.coffee
        main.js.coffee
        router.js.coffee
    layouts/
    stylesheets/
    index.html.erb
```

## Installation

Check out the [release page](https://github.com/alexlafroscia/middleman-ember-starter/releases) and download the latest one.  You can also download a .zip archive of the current master branch from [here](https://github.com/alexlafroscia/middleman-ember-starter/archive/master.zip).

Unzip the project and move it into the directory `~/.middleman`.  That's it!

Alternatively, if you want to use Git to install the template, navigate into `~/.middleman` and run the command from there

```bash
git@github.com:alexlafroscia/middleman-ember-starter.git
rm -rf .git
```
Make sure to run both commands, or else the `.git` directory will get copied into all of your new projects as well, and I'm sure you don't want that!

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
