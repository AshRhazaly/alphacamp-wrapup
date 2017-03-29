GEM toolkit
============

Rails (Standard)
-----------------
```ruby
gem 'slim-rails'
gem 'bootstrap'
gem 'bootstrap_form'
gem 'font-awesome-rails'
gem 'rails_admin'
gem 'ffaker'
gem 'figaro'
gem 'pry-rails'
gem 'hirb'
```

Rails (TDD)
------------
```ruby
group :development, :test do
  gem 'factory\_girl\_rails'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'guard-rspec', require: false
  gem 'simplecov', require: false
  gem 'rails-controller-testing'
  gem 'capybara'
end
```

Rails (Common)
---------------
```ruby
gem 'kaminari'
gem 'stripe-rails'
gem 'devise'
gem 'carrierwave'
```

Rails (External)
----------------
```ruby
gem 'metric_fu'
gem 'annotate'
gem 'yard'
```