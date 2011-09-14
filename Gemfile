source 'http://rubygems.org'

gem 'rails', '3.1.0.rc8'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# 認証
gem 'devise', :git => "https://github.com/plataformatec/devise.git"
gem "oauth-plugin", "=0.4.0.pre7"
gem "oa-oauth", :require => "omniauth/oauth" 

# view
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0.rc"
  gem 'coffee-rails', "~> 3.1.0.rc"
  gem 'uglifier'
end
gem 'jquery-rails'

gem "kaminari", :git => "https://github.com/amatsuda/kaminari.git"
gem "simple-navigation", :git=>"https://github.com/andi/simple-navigation.git"
gem 'dynamic_form'

# Controller
gem 'strut', :git => 'https://github.com/kuruma-gs/strut.git'


# Model
gem 'current', :git=>'https://github.com/kuruma-gs/current.git'
gem "stateflow", :git => "https://github.com/nunukim/stateflow.git"
## 画像
gem "mini_magick",:git=>"https://github.com/probablycorey/mini_magick.git"
gem "carrierwave",:git=>"https://github.com/jnicklas/carrierwave.git"


# DB
gem "mongoid"
gem "bson_ext"



# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

# RSpec
group :test do
  # Pretty printed test output
  gem 'turn', :require => false

  # RSpec と仲間たち
  gem "rspec"
  gem "rspec-rails"
  gem 'autotest-rails'
  gem 'autotest'
  gem 'mongoid-rspec',:git=>"https://github.com/evansagge/mongoid-rspec.git"
  gem 'webmock', :git=>"https://github.com/bblimke/webmock.git"
  gem 'spork', :git => "https://github.com/timcharper/spork.git"
  gem 'steak',:git=>'https://github.com/cavalle/steak.git'
  gem 'capybara',:git=>'https://github.com/jnicklas/capybara.git'
  gem 'resque_spec', :git=>"https://github.com/nunukim/resque_spec.git"

  ### Mac のみ
  if `uname` =~ /Darwin/
    gem 'rb-fsevent'
    gem 'growl'
    gem 'autotest-fsevent'
    gem 'autotest-growl'
  end

  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-cucumber'

end

group :development, :test do
  gem "factory_girl_rails",:git=>"https://github.com/thoughtbot/factory_girl_rails.git"
end

# 便利ツール
group :development do
  # Console 用ユーティリティ
  gem "wirble"
end




