# Middleman + Ember + Bower Starter Project

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

## How to Use

###### 1. Make your own copy

1. Fork the project
2. Clone your fork

###### 2. Bundle

```bash
bundle install
```

###### 3. Bower

```bash
bower install
```

###### 4. Create

```bash
middleman server
```
