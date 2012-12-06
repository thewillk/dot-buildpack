Dynamic Heroku Buildpack
========================

This lets the buildpack be checked into the repo.

Installation
------------

  * Create your heroku application
  * Supply the `BUILDPACK_URL` env variable 

```
heroku config:add BUILDPACK_URL="https://github.com/djukami/dot-buildpack.git"
```

Usage
-----

Create your own `.buildpack/compile` and `.buildpack/release` files per Heroku's Buildpack API.
