source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'pg'
#gem 'mysql2'

group :assets do
  #gem 'sass-rails'  #,  '~> 3.2.3'
  gem 'coffee-rails' #, '~> 3.2.1'
  gem 'less-rails'

  gem 'therubyracer', :platforms => :ruby
  gem 'execjs'
  gem 'uglifier' #, '>= 1.0.3'

  gem 'sprockets-dotjs', :git => 'git://github.com/jamifsud/sprockets-dotjs.git'
  #gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'
end

group :test, :development do
  #develop section
  gem 'capistrano'
  gem 'capistrano_colors'
  gem 'rvm-capistrano'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'

  #test section
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false

  gem 'ruby-prof'
  gem 'guard' # inspect file change
  #gem 'growl_notify' # mac osx notification
  #gem 'growl'
  gem 'factory_girl_rails'
end

# required test gem
group :tools do
  gem 'guard-test'
  gem 'simplecov', :require => false #covergae test show GUI
end

#JS
gem 'jquery-rails'
#gem 'bootstrap-datepicker-rails', :require => 'bootstrap-datepicker-rails', :git => 'git://github.com/Nerian/bootstrap-datepicker-rails.git'

#Ruby
#core
  #gem 'haml-rails'
  gem 'slim'
  gem 'slim-rails'
  gem 'squeel'
  gem 'responders'
  #gem 'oj' #json lib - load model class before Oj.load() else you get nil
#auth
  gem 'devise'
  #gem 'twitter_oauth'
  gem 'cancan'
#file proccess
  gem 'carrierwave' #upload file
  #gem 'pdfkit' #PDF from html
  #gem 'roo' #read & write Excel
#localization
  gem 'russian', '~> 0.6.0'
#admin area
  #gem 'rails_admin'
#rails server
  gem 'unicorn'

#fixes lib
gem 'libv8', '~> 3.11.8'



