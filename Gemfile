# # frozen_string_literal: true

# source "https://rubygems.org"
# gemspec
# group :jekyll_plugins do
#     gem "jekyll-feed", "~> 0.6"
#     gem "jekyll-sitemap"
#     gem "jekyll-paginate"
#     gem "jekyll-seo-tag"
#     gem 'jekyll-redirect-from'
# end

source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# To use GitHub Pages, comment the "gem "jekyll"" below and
# uncomment the "gem "github-pages"" line.
# To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
end

# Theme: Bulma Clean Theme
gem "bulma-clean-theme"

# Without this, running the website locally (bundle exec jekyll serve)
# may fail with versions of ruby >= 3.0.0
gem "webrick", "~> 1.7"