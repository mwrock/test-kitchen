# -*- encoding: utf-8 -*-
source "https://rubygems.org"
gemspec

gem "mixlib-install", :github => "chef/mixlib-install", :branch => "master"

group :guard do
  gem "guard-minitest"
  gem "guard-cucumber", "~> 1.4"
  gem "guard-rubocop"
  gem "guard-yard"
end

group :test do
  gem "codeclimate-test-reporter", :require => nil
end
