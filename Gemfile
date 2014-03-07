source 'https://rubygems.org'

gem 'berkshelf', '~> 2.0.14'

group :unit do
  gem 'foodcritic', '~> 3.0'
  gem 'rubocop', '~> 0.18.0'
  gem 'chefspec', '~> 3.2.0'
end

group :integration do
  gem 'test-kitchen', '~> 1.2'
  gem 'kitchen-vagrant'
end

group :release do
  gem 'rspec_junit_formatter'
  gem 'rubocop-checkstyle_formatter'
  gem 'thor-foodcritic', '~> 1.1'
  gem 'thor-scmversion', '~> 1.4'
end

group :development do
  gem 'rake', '~> 10.1'
  gem 'serverspec', '~> 0.14.2'
  gem 'guard', '~> 1.8'
  gem 'guard-rubocop', '~> 0.2'
  gem 'guard-foodcritic', '~> 1.0'
  gem 'guard-kitchen', '~> 0.0'
  gem 'guard-rspec', '~> 3.0'
  gem 'rb-fsevent', :require => false
  gem 'rb-inotify', :require => false
  gem 'terminal-notifier-guard', :require => false
end
