source 'https://ruby.taobao.org'

gem 'rails', '4.2.6'
gem 'mysql2'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'whenever', :require => false
gem 'sinatra', '~> 1.4.7', :require => nil
gem 'sidekiq', '>= 3.5.1'
gem 'cancancan', '~> 1.10'
gem 'rest-client'
gem 'dalli'
gem 'china_sms', git: "git://github.com/villins/china_sms.git"
gem 'aasm', '~> 4.1'
gem 'quiet_assets', group: :development
#图片上传
gem 'carrierwave'
gem 'carrierwave-upyun', '0.1.5'
gem 'rails-assets-for-upyun', '>= 0.0.9'
#支付相关
gem 'alipay', '~> 0.12.0'
gem 'wx_pay', '~> 0.6.0'
#wepay回调参数接收
gem 'actionpack-xml_parser'
#paypal
gem 'paypal-sdk-merchant'
gem 'activeresource'


# 后台
gem 'semantic-ui-sass', github: 'doabit/semantic-ui-sass'
gem 'kaminari'

group :development, :test do
  gem 'byebug'
  gem 'spring'
  gem 'rspec-rails', '~> 3.1.0'
  gem 'factory_girl_rails', "~> 4.4.1"
  gem 'pry-rails'
  gem 'pry-nav'
  gem 'thin'

  gem 'awesome_print'

  #fake data
  gem 'faker', "~> 1.4.3"
  gem 'database_cleaner', "~> 1.3.0"
  #validate model
  gem "shoulda-matchers"
  gem 'rspec-collection_matchers'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'capistrano', '3.4.0'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-rvm'
  gem 'capistrano-sidekiq'
  gem 'capistrano-passenger'
end

