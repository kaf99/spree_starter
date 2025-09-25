source "https://rubygems.org"

ruby '3.3.0'

gem 'rails', '~> 8.0.0'
gem "pg", "~> 1.6"
gem "puma", ">= 5.0"

# Payment Integrations
gem 'spree_razorpay', git: 'https://github.com/kaf99/spree_razorpay.git', branch: 'main'
gem "spree_stripe"
gem "spree_paypal_checkout", "~> 0.5"

# JS + Hotwire
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"

# JSON & API
gem "jbuilder"

# JS runtime
gem 'mini_racer', platforms: :ruby

# Redis / Background jobs
gem "redis", ">= 4.0.1"
gem 'sidekiq'

# Auth
gem "devise"

# Monitoring & Error tracking
gem 'sentry-ruby'
gem 'sentry-rails'
gem 'sentry-sidekiq'

# Image uploads
gem "image_processing", "~> 1.13"

# Spree gems
spree_opts = '~> 5.1'
gem "spree", spree_opts
gem "spree_emails", spree_opts
gem "spree_sample", spree_opts
gem "spree_admin", spree_opts
gem "spree_storefront", spree_opts
gem "spree_i18n"
gem "spree_google_analytics", "~> 1.0"
gem "spree_klaviyo", "~> 1.0"

# Spree Extensions
gem 'spree_product_reviews', git: 'https://github.com/kaf99/spree_product_reviews.git', branch: 'main'

# Development & Test
group :development, :test do
  gem "debug", platforms: %i[mri windows]
  gem 'brakeman'
  gem 'dotenv-rails', '~> 3.1'
  gem 'rubocop', '~> 1.23'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'pry'
  gem 'pry-remote'
end

group :development do
  gem "foreman"
  gem "web-console"
  gem "letter_opener"
  gem 'solargraph'
  gem 'solargraph-rails'
  gem 'ruby-lsp'
  gem 'ruby-lsp-rails'
end

group :test do
  gem 'spree_dev_tools'
  gem 'rails-controller-testing'
end

# Windows only
gem "tzinfo-data", platforms: %i[windows jruby]

# Boot optimization
gem "bootsnap", require: false
