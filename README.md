# StreetEasy Frontend Developer Work Sample

This is the work sample to be completed by applicants for the frontend developer position at StreetEasy.

## Instructions

StreetEasy are creating a new feature which will allow users to compare rental listings - and your task is to implement the "list" part. Using the [following design image](https://www.dropbox.com/s/5mnft7ayw9rapbh/Front%20End%20Code%20Exercise.png?dl=0), implement the HTML, CSS and any JavaScript (if necessary) for the listings and the "add" button. Please note that your solution should be responsive and as close to the designs as possible. We also have the [original sketch file and assets](https://www.dropbox.com/s/x96cw29w1fuxmz6/designexercise_assets.zip?dl=0) if you'd like to use those.

Your solution should also work with the existing application structure. Make any assumptions that you need to. We are evaluating your implementation based on code cleanliness, organization and attention to detail. If you want to add any extra touches that showcase your skills, please feel free to do so!

## Getting up and running

To keep this exercise as close as possible to real projects at StreetEasy, we have used the same programming language, template engine and css pre-processor that we use in production. The following instructions assume you are running OS X.

### Install the correct ruby and gems

We use [rbenv](https://github.com/rbenv/rbenv) to manage our ruby version. If you have [homebrew](http://brew.sh) then you can install this with:

```
$ brew update && brew install rbenv
```

Next, from the root of this project directory, install the correct version of ruby, bundler and associated gems:

```
$ rbenv install
$ gem install bundler
$ bundle install
```

### Start the application

This is a [Sinatra](http://www.sinatrarb.com/documentation.html) application. To run the application:

```
$ rerun 'rackup'
```

If everything has installed correctly, this should start an application on [http://localhost:9292/](http://localhost:9292/).

## Submitting your solution

Once your exercise is complete, commit your work, create a patch file and send that to us. Please _do not_ fork this pubic GitHub repo. We don't want other people copying your work! To create the patch:

```
git format-patch origin/master --stdout > fe-ws.patch
```

Good luck and enjoy!