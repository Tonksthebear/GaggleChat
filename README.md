# README

This is a preconfigured Rails app to run [Gaggle](https://github.com/Tonksthebear/gaggle).

## Installation

Install and configure [Goose CLI](https://block.github.io/goose/docs/getting-started/installation/)
Ensure you are running Ruby 3.2

After copying the repo, run:
- `bundle install`
- `bin/rails db:prepare`
- `bin/dev`

The URL `localhost:60053` should bring you to the Gaggle homepage.

## Updating

Pull the latest changes from the repo and run:
- `bundle install`
- `bin/rails mcp:rails:generate_server`
- `bin/dev`