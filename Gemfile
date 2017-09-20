source "https://rubygems.org"

# Make sure Jekyll 3.3 is running
gem "jekyll", "~> 3.4"

# The theme for the site
gem "alembic-jekyll-theme", "~> 2.2"

# The plugins for the site
group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-mentions"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
  gem "jekyll-default-layout"
  gem "jekyll-feed"
  gem "jemoji"
  gem 'jekyll-twitter-plugin'
end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end

require 'rbconfig'
  if RbConfig::CONFIG['target_os'] =~ /darwin(1[0-3])/i
    gem 'rb-fsevent', '<= 0.9.4'
  end
