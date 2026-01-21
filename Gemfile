# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.4", ">= 7.4.1"

# Add the jekyll-polyglot plugin
gem "jekyll-polyglot"

gem "html-proofer", "~> 5.0", group: :test

# Use the generic :windows platform symbol (replaces :mingw, :x64_mingw, :mswin)
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# wdm only on Windows
gem "wdm", "~> 0.2.0", platforms: :windows
