# jekyll-docker-web

bundle init

bundle add jekyll --version "~>3.9.0"

bundle exec jekyll new --force --skip-bundle .

bundle add webrick

bundle install

bundle update

bundle exec jekyll serve --livereload