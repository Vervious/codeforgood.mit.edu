# codeforgood.mit.edu

This is the website for MIT Code for Good.

## Building

Run `bundle install` to fetch dependencies.

Run `bundle exec jekyll build` to build the site.

## Web Server Configuration

The web server should be configured to display `/404.html` for HTTP 404 errors.

## Development Workflow

The `master` branch contains GPG-signed tagged releases (tagged as `vX.X.X`).

The `develop` branch is where most of the development happens.

Release branches are named `release/X.X.X`, and hotfix branches are named
`hotfix/*`. Feature branches are named `feature/*`.
