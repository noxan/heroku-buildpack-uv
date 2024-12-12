Heroku buildpack: UV
====================

This is a [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for [Astral's UV](https://docs.astral.sh/uv/).

Usage
-----

Example usage:

    $ ls
    uv init

    $ heroku create --buildpack https://github.com/noxan/heroku-buildpack-uv.git

    $ git push heroku main
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> UV app detected
    -----> Found a pyproject.toml

The buildpack will require your app to have a `pyproject.toml` in the root.
