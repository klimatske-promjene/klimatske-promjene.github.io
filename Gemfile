source 'https://rubygems.org'

# GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem 'jekyll-scholar'
  gem 'jekyll-redirect-from'
  gem 'jekyll-sitemap', '~> 1.4'
  gem 'jekyll-feed', '~> 0.12'
  gem 'jekyll-microtypo'
  gem 'jekyll-figure'
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Specific gems for citation handling in Jekyll Scholar
gem "citeproc", "~> 1.0"
gem "csl-styles"

# Misc dependencies
gem "tzinfo", ">= 1", "< 3"
gem "tzinfo-data"
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
gem "csv"
gem "base64"
gem "observer"

# Ensure compatibility across platforms
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "ffi"
end





