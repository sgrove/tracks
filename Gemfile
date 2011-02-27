source "http://rubygems.org"

gem 'rails', '2.3.11', :path => 'vendor/rails/railties'
gem 'datanoise-actionwebservice', '2.3.2', :path => 'vendor/gems/datanoise-actionwebservice-2.3.2'
gem 'highline', '1.5.0', :path => 'vendor/gems/highline-1.5.0'
gem 'soap4r', '1.5.8', :path => 'vendor/gems/soap4r-1.5.8'
gem 'ruby-openid', '2.1.2', :path => 'vendor/gems/ruby-openid-2.1.2', :require => 'openid'
gem 'RedCloth'
gem 'sanitize'
gem 'rack', '1.1.0'
gem 'will_paginate', '>= 2.3.15'
gem 'has_many_polymorphs'
gem 'sqlite3'
gem 'rubycas-client', :require => 'casclient'

group :test do
  gem 'rspec-rails', '< 2.1.0'
  gem "flexmock"
  gem "ZenTest", ">=4.0.0", :require => "zentest"
  gem "hpricot"
  gem "hoe"
  gem 'webrat', '>=0.7.0', :require => false
  gem 'rspec-rails', '<2.1.0', :require => false
  gem "factory_girl"
end

group :cucumber do
  gem 'cucumber', '<0.10.0', :require => false
  gem 'cucumber-rails', '>=0.3.2', :require => false
  gem 'gherkin', '2.2.9'  , :require => false
  gem 'database_cleaner', '>=0.5.0', :require => false
  gem 'webrat', '>=0.7.0', :require => false
end

group :selenium do
  gem 'database_cleaner', '>=0.5.0', :require => false
  gem 'selenium-client',  :require => false
  gem 'mongrel'  # required by webrat for selenium
end
