Dynamic Heroku Buildpack
========================

This lets the buildpack be checked into the repo.

Installation
------------

  * Create your heroku application
  * Supply the `BUILDPACK_URL` env variable 

```
heroku config:add BUILDPACK_URL="BUILDPACK_URL: https://github.com/djukami/dot-buildpack.git"
```

Place your buildpack scripts in .buildpack in your repo.
