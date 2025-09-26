source "https://rubygems.org"
# This is the recommended setup for GitHub Pages
# It will automatically use compatible versions of all dependencies
gem "github-pages", group: :jekyll_plugins

# If you want to use a specific Jekyll version, uncomment the line below
# and comment out the github-pages line above
# gem "jekyll", "~> 4.3.2"
# gem "minima", "~> 2.5"

# Lock the Ruby version
ruby "~> 3.0.0"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Platform-specific gems
platforms :jruby do
  # JRuby-specific gems
  gem "tzinfo"
  gem "http_parser.rb", "~> 0.6.0"  # Required for webrick on JRuby
end
