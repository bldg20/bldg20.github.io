source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'jekyll-sitemap'
gem 'octopress', '~> 3.0.0.rc.12'

group :test do
  gem 'html-proofer'
end
