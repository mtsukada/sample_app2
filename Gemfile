# gemを加えたら、rails sを忘れない
source 'https://rubygems.org'
ruby '2.1.0'

# default
gem 'rails', '4.1.0'
gem 'mysql2'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'bcrypt-ruby', '~> 3.1.2'


group :doc do
    # bundle exec rake doc:rails generates the API under doc/api.
    gem 'sdoc', require: false
end

# custom added by myself
gem 'rails-i18n'
gem 'will_paginate'
gem 'thin'



group :development, :test do
    # rspec
    gem 'rspec-rails'
    gem 'guard-rspec', '2.5.0'
    gem 'spork-rails', '4.0.0'
    gem 'guard-spork', '1.5.0'
    gem 'childprocess', '0.3.6'

    gem 'rails-erd' # ER図
    gem 'annotate' # モデルにカラム名記載
    gem 'faker', '0.3.1' # テスト用画像
    gem 'better_errors' # エラー画面をわかりやすく整形してくれる
    gem 'binding_of_caller' # better_errorsの画面上にirb/pry(PERL)を表示する
    gem 'factory_girl_rails', '4.2.1'
    gem 'pry'
    gem 'pry-doc'
    gem 'pry-rails'

    # TwitterBootstrapのためのgem 'twitter-bootstrap-rails' これはいれず手動で入れる
    gem 'libv8', '~> 3.11.8.13'
    gem 'less-rails'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'growl', '1.0.3'
end

group :production do
    gem 'rails_12factor'
end

