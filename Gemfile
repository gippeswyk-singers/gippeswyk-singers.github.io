source "https://rubygems.org"

# Set ruby version as per https://pages.github.com/versions/
# See also https://github.com/github/pages-gem/issues/752
ruby '3.3.4'

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
# gem "jekyll", "~> 4.3.3"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"
gem "jekyll-remote-theme"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-mentions"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
  gem "jekyll-commonmark"
  gem "jekyll-include-cache"
  gem "jemoji"  
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Following gems reported missing by Github actions (https://github.com/gippeswyk-singers/gippeswyk-singers.github.io/actions) 
gem "webrick", "~> 1.9"

gem "i18n", "~> 1.14"

gem "rexml", "~> 3.3"

gem "activesupport", "~> 7.2"

gem "concurrent-ruby", "~> 1.3"

gem "faraday", "~> 2.12"

gem "execjs", "~> 2.10"

gem "logger", "~> 1.6"

gem "minitest", "~> 5.25"

gem "faraday-net_http", "~> 3.3"

gem "json", "~> 2.7"

gem "uri", "~> 0.13.1"
