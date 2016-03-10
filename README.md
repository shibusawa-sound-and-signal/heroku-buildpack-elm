## Minimal Heroku Elm Buildpack

This buildpack installs your elm dependencies. It assumes that it will be chained with the nodejs buildpack: https://github.com/heroku/heroku-buildpack-nodejs

### Configuration

1. Create a package.json (http://browsenpm.org/package.json) for your project if you don't already have one.
2. Add elm to the dependencies.
