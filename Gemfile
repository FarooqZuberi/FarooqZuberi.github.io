#source "https://rubygems.org"
#gemspec
#gem 'github-pages'



source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']


## Optional setup for Travis-CI
gem 'html-proofer'       # useful for Travis-CI 
gem 'scss_lint'          # useful for Travis-CI