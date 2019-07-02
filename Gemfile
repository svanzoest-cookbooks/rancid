# frozen_string_literal: true

source 'https://rubygems.org'

gem 'berkshelf', '~> 7.0.8'

group :unit do
  gem 'chefspec', '~> 7.4.0'
  gem 'foodcritic', '~> 16.0.0'
  gem 'rubocop', '~> 0.72.0'
end

group :integration do
  gem 'kitchen-docker', :require => false
  gem 'kitchen-vagrant', :require => false
  gem 'test-kitchen', '~> 2.2.5'
end

group :release do
  gem 'rspec_junit_formatter'
  gem 'rubocop-checkstyle_formatter'
end

group :development do
  gem 'guard', '~> 2.13.0'
  gem 'guard-foodcritic', '~> 3.0.0'
  gem 'guard-kitchen', '~> 0.1.0'
  gem 'guard-rspec', '~> 4.7.3'
  gem 'guard-rubocop', '~> 1.3.0'
  gem 'rb-fsevent', :require => false
  gem 'rb-inotify', :require => false
  gem 'terminal-notifier-guard', :require => false
end
