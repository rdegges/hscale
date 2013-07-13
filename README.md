# hscale

Automatically scale your Heroku applications.


## Purpose

I've been using Heroku for a while, and one of the things I've always needed is
a reliable autoscaling solution that allows me to:

- Automatically scale my dynos up and down.
- Automatically scale my workers up and down.
- Automatically scale my addons up and down.
- Perform scaling based on arbitrary metrics.

Unfortunately, none of the existing solutions are flexible enough to do what
needs to be done -- hence -- hscale.

hscale is meant to be a general purpose monitoring and scaling tool for Heroku
applications, which, by default, ships with support for 99% of your scaling
needs.

Anything that hscale doesn't support can be easily added, so don't be afraid to
get your hands dirty!  The more contributers -- the merrier ^^
