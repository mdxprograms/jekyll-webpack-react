## Jekyll Starter

This starter uses webpack for react/es6

It also includes a Rakefile that runs multi threads
to run `bundle exec jekyll s -L` (which includes jekyll-livereload) and `webpack -w` at the same time.

This starter has borrowed most of this project aside from the custom rake tasks which manage the dev setup:
https://github.com/allizad/jekyll-webpack

### Setup

- `npm install -g webpack`
- `npm install`
- `bundle install`
- `rake start`
