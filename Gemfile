# frozen_string_literal: true

source "http://rubygems.org"

gemspec

# apps can also use will_paginate so there's no dependency in gemspec
gem 'kaminari'
gem 'codemirror-rails', github: 'zinsbaustein/codemirror-rails', branch: 'rails6'

group :development do
  gem "listen",       "~> 3.1.5"
  gem "web-console",  "~> 3.5.1"
end

group :test do
  gem "coveralls",                "~> 0.8.21", require: false
  gem "diffy",                    "~> 3.2.0"
  gem "equivalent-xml",           "~> 0.6.0"
  gem "mocha",                    "~> 1.3.0", require: false
  gem "rails-controller-testing", "~> 1.0.2"
end
