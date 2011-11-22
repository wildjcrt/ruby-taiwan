source 'http://rubygems.org'

gem "rails", "3.1.1"
gem "bson", "1.3.1"
gem "bson_ext", "1.3.1"
gem "mongoid", "2.2.4"
# 上传组件
gem 'carrierwave', '0.5.6'
gem 'carrierwave-mongoid', '0.1.2', :require => 'carrierwave/mongoid'
# 图像处理
gem 'mini_magick','3.3'
# Mongoid 辅助插件
gem 'mongo-rails-instrumentation','0.2.4'
gem "mongoid-eager-loading",'0.3.1'
# Mongoid 使用自增整形ID
gem 'mongoid_auto_increment_id', "0.2.2"
# 用户系统
gem "devise", "1.4.5"
# 分页
gem 'will_paginate', '3.0.pre2'  
# 三方平台 OAuth 验证登陆
gem 'omniauth', '0.3.0'
gem "oa-openid", '0.3.0'
# Rails cache 存放到 Redis
gem 'dalli', '1.1.1'
# 搜索相关的组件
gem 'chinese_pinyin', '0.4.1'
gem "rmmseg-cpp-huacnlee", "0.2.8"
gem 'redis-search', '0.6.3'
# Rails I18n
gem "rails-i18n","0.1.8"
# Redis 命名空间
gem 'redis-namespace','~> 1.0.2'
# 将一些数据存放入 Redis
gem "redis-objects", "0.5.2"
# Markdown 格式
gem "rdiscount","1.6.8"
# HTML 处理
gem "nokogiri", "1.5.0"
gem "jquery-rails", "1.0.16"
# Auto link
gem "rails_autolink", ">= 1.0.4"
# YAML 配置信息
gem "settingslogic", "~> 2.0.6"
gem "cells", "3.6.7"
gem "resque", "~> 1.19.0", :require => "resque/server"
gem "resque_mailer", '2.0.2'
gem "aws-ses", "~> 0.4.3"
gem 'mail_view', :git => 'git://github.com/37signals/mail_view.git'
gem "daemon-spawn", "~> 0.4.2"
gem "unicorn"

group :assets do
  gem 'sass-rails', "  ~> 3.1.4"
  gem 'coffee-rails', "~> 3.1.1"
  gem 'uglifier'
end

group :development do
	gem 'capistrano', '2.9.0'
end

group :test do
  gem 'factory_girl_rails'
end
