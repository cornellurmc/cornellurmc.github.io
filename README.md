# How to run on your computer

First, install jekyll by following the instructions [here](https://jekyllrb.com/docs/installation/)

Then, install this project's dependencies:

    bundle install 

run `sass assets/sass/main.scss assets/css/main.css assets/css/main.css` to generate css from the sass file. (This might not be the idiomatic way to do this with jekyll, might have to change in the future)

To run the webserver on your computer, run:

    bundle exec jekyll serve

# How to deploy the website

In order to deploy, commit what you want to be visible on the main site to the master branch, then push your master branch to the github repository.
