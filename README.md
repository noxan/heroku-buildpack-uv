Heroku buildpack: UV
====================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [Astral's UV](https://docs.astral.sh/uv/).

Usage
-----

Example usage:

    $ ls
    uv init

    $ heroku create --buildpack http://github.com/noxan/heroku-buildpack-uv.git

    $ git push heroku main
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> HelloFramework app detected
    -----> Found a hello.txt

The buildpack will require your app to have a `pyproject.toml` in the root.
