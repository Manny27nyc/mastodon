# frozen_string_literal: true

source 'https://rubygems.org'
ruby '>= 2.5.0', '< 3.0.0'

gem 'pkg-config', '~> 1.4'

gem 'puma', '~> 5.1'
gem 'rails', '~> 6.1.7.5'
gem 'sprockets', '~> 3.7.2'
gem 'thor', '~> 1.0'
gem 'rack', '~> 2.2.3'

gem 'hamlit-rails', '~> 0.2'
gem 'pg', '~> 1.2'
gem 'makara', '~> 0.5', '>= 0.5.0'
gem 'pghero', '~> 2.7', '>= 2.7.4'
gem 'dotenv-rails', '~> 2.8', '>= 2.8.0'

gem 'aws-sdk-s3', '~> 1.87', require: false
gem 'fog-core', '<= 2.1.0'
gem 'fog-openstack', '~> 0.3', require: false
gem 'paperclip', '~> 6.1', '>= 6.1.0'
gem 'paperclip-av-transcoder', '~> 0.6'
gem 'streamio-ffmpeg', '~> 3.0'
gem 'blurhash', '~> 0.1'

gem 'active_model_serializers', '~> 0.10', '>= 0.10.13'
gem 'addressable', '~> 2.7'
gem 'bootsnap', '~> 1.5', require: false
gem 'browser'
gem 'charlock_holmes', '~> 0.7.7'
gem 'iso-639'
gem 'chewy', '~> 5.2', '>= 5.2.0'
gem 'cld3', '~> 3.4.1'
gem 'devise', '~> 4.8', '>= 4.8.0'
gem 'devise-two-factor', '~> 4.0', '>= 4.0.0'

group :pam_authentication, optional: true do
  gem 'devise_pam_authenticatable2', '~> 9.2'
end

gem 'net-ldap', '~> 0.17'
gem 'omniauth-cas', '~> 2.0'
gem 'omniauth-saml', '~> 1.10'
gem 'omniauth', '~> 1.9'
gem 'omniauth-rails_csrf_protection', '~> 1.0', '>= 1.0.0'

gem 'color_diff', '~> 0.1'
gem 'discard', '~> 1.2', '>= 1.2.1'
gem 'doorkeeper', '~> 5.5', '>= 5.5.0'
gem 'ed25519', '~> 1.2'
gem 'fast_blank', '~> 1.0'
gem 'fastimage'
gem 'hiredis', '~> 0.6'
gem 'redis-namespace', '~> 1.8'
gem 'health_check', git: 'https://github.com/ianheggie/health_check', ref: '0b799ead604f900ed50685e9b2d469cd2befba5b'
gem 'htmlentities', '~> 4.3'
gem 'http', '~> 4.4'
gem 'http_accept_language', '~> 2.1'
gem 'httplog', '~> 1.4.3'
gem 'idn-ruby', require: 'idn'
gem 'kaminari', '~> 1.2', '>= 1.2.2'
gem 'link_header', '~> 0.0'
gem 'mime-types', '~> 3.3.1', require: 'mime/types/columnar'
gem 'nilsimsa', git: 'https://github.com/witgo/nilsimsa', ref: 'fd184883048b922b176939f851338d0a4971a532'
gem 'nokogiri', '~> 1.11'
gem 'nsa', '~> 0.2', '>= 0.2.8'
gem 'oj', '~> 3.10'
gem 'ox', '~> 2.14'
gem 'parslet'
gem 'parallel', '~> 1.20'
gem 'posix-spawn'
gem 'pundit', '~> 2.1', '>= 2.1.1'
gem 'premailer-rails', '>= 1.12.0'
gem 'rack-attack', '~> 6.3'
gem 'rack-cors', '~> 1.1', require: 'rack/cors'
gem 'rails-i18n', '~> 6.0', '>= 6.0.0'
gem 'rails-settings-cached', '~> 0.7', '>= 0.7.0'
gem 'redis', '~> 4.2', require: ['redis', 'redis/connection/hiredis']
gem 'mario-redis-lock', '~> 1.2', require: 'redis_lock'
gem 'rqrcode', '~> 1.2'
gem 'ruby-progressbar', '~> 1.11'
gem 'sanitize', '~> 5.2'
gem 'scenic', '~> 1.5', '>= 1.5.5'
gem 'sidekiq', '~> 6.1'
gem 'sidekiq-scheduler', '~> 3.0'
gem 'sidekiq-unique-jobs', '~> 6.0'
gem 'sidekiq-bulk', '~>0.2.0'
gem 'simple-navigation', '~> 4.2', '>= 4.2.0'
gem 'simple_form', '~> 5.1', '>= 5.1.0'
gem 'sprockets-rails', '~> 3.3', '>= 3.3.0', require: 'sprockets/railtie'
gem 'stoplight', '~> 2.2.1'
gem 'strong_migrations', '~> 0.7', '>= 0.7.5'
gem 'tty-prompt', '~> 0.23', require: false
gem 'twitter-text', '~> 1.14'
gem 'tzinfo-data', '~> 1.2020'
gem 'webpacker', '~> 5.2', '>= 5.2.2'
gem 'webpush'
gem 'webauthn', '~> 3.0.0.alpha1'

gem 'json-ld'
gem 'json-ld-preloaded', '~> 3.1'
gem 'rdf-normalize', '~> 0.4'

group :development, :test do
  gem 'fabrication', '~> 2.21'
  gem 'fuubar', '~> 2.5'
  gem 'i18n-tasks', '~> 0.9', '>= 0.9.34', require: false
  gem 'pry-byebug', '~> 3.9'
  gem 'pry-rails', '~> 0.3'
  gem 'rspec-rails', '~> 4.1', '>= 4.1.0'
end

group :production, :test do
  gem 'private_address_check', '~> 0.5'
end

group :test do
  gem 'capybara', '~> 3.34'
  gem 'climate_control', '~> 0.2'
  gem 'faker', '~> 2.15'
  gem 'microformats', '~> 4.2'
  gem 'rails-controller-testing', '~> 1.0'
  gem 'rspec-sidekiq', '~> 3.1'
  gem 'simplecov', '~> 0.21', require: false
  gem 'webmock', '~> 3.11'
  gem 'parallel_tests', '~> 3.4'
  gem 'rspec_junit_formatter', '~> 0.4'
end

group :development do
  gem 'active_record_query_trace', '~> 1.8'
  gem 'annotate', '~> 3.2', '>= 3.2.0'
  gem 'better_errors', '~> 2.9'
  gem 'binding_of_caller', '~> 1.0'
  gem 'bullet', '~> 6.1', '>= 6.1.3'
  gem 'letter_opener', '~> 1.7'
  gem 'letter_opener_web', '~> 1.4', '>= 1.4.1'
  gem 'memory_profiler'
  gem 'rubocop', '~> 1.7', require: false
  gem 'rubocop-rails', '~> 2.10', '>= 2.10.0', require: false
  gem 'brakeman', '~> 4.10', require: false
  gem 'bundler-audit', '~> 0.7', require: false

  gem 'capistrano', '~> 3.17'
  gem 'capistrano-rails', '~> 1.6'
  gem 'capistrano-rbenv', '~> 2.2'
  gem 'capistrano-yarn', '~> 2.0'

  gem 'stackprof'
end

group :production do
  gem 'lograge', '~> 0.12', '>= 0.12.0'
  gem 'redis-rails', '~> 5.0'
end

gem 'concurrent-ruby', require: false
gem 'connection_pool', require: false

gem 'xorcist', '~> 1.1'
gem 'pluck_each', '~> 0.2.0'
