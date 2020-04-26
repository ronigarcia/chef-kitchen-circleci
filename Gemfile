# -*- mode: ruby -*-
# vi: set ft=ruby :

source 'https://rubygems.org'

gem 'rake'
gem 'berkshelf', '~> 4.0'
gem 'faraday', '~> 0.9'
#gem 'httpclient', '~> 2.8.3'

group :integration do
  gem 'test-kitchen', '~> 1.2'
end

group :vagrant do
  gem 'vagrant-wrapper', '~> 2.0'
  gem 'kitchen-vagrant', '~> 0.18'
end

group :docker do
  gem 'kitchen-docker', '~> 2.1'
end