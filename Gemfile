# frozen_string_literal: true

source "https://rubygems.org"

# core app
gem "rails", "~> 7.1.4", ">= 7.1.4.2"
gem "sqlite3", "~> 1.7"
gem "puma", ">= 5.0"
gem "tzinfo-data", platforms: [:windows, :jruby]

gem "bootsnap", require: false
gem "rubocop-shopify", ">= 2.16.0", require: false

# docs
gem "jekyll", "~> 4.3", ">= 4.3.4"
gem "jekyll-redirect-from", "~> 0.16"

# command line
gem "cli-ui", "~> 2.2", require: false
gem "tty-option", "~> 0.3", require: false

# generate taxonomy mappings
gem "qdrant-ruby", ">= 0.9.8", require: "qdrant"
gem "ruby-openai", ">= 7.2.0"
gem 'dotenv', groups: [:development, :test]

group :development, :test do
  gem "debug", platforms: [:mri, :windows]
  gem "mocha"
  gem "factory_bot_rails", "~> 6.4", ">= 6.4.4"
  gem "minitest-hooks", "~> 1.5"
end
