source "https://rubygems.org"

# Specify Ruby version
ruby '3.0.0'

# Use GitHub Pages gem, which includes Jekyll and other dependencies
gem "github-pages", group: :jekyll_plugins

# Specify Nokogiri version
gem 'nokogiri', '~> 1.11.0'

# Jekyll version
gem "jekyll", "~> 4.3.0"

# For Windows platform
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins', '~> 2.5'
  gem "webrick", "~> 1.8"
end
