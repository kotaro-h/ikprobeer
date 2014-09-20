source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '4.0.4'

# DBアダプタ
gem 'pg', '0.17.1'

# 認証関係
gem 'devise'
gem 'omniauth', '1.2.1'
gem 'omniauth-facebook', '1.6.0'
gem 'omniauth-twitter'
gem 'koala', '1.8.0'

# # パンくず用
gem 'breadcrumbs_on_rails', '2.3.0'

# jQuery 叩くため
gem 'jquery-rails', '3.1.0'

# # Coffeescript helpers for rails
gem 'coffeebeans', '1.0.1'

# # 管理画面
# gem 'rails_admin', '0.6.2'

# # 画像処理関係
# # gem 'rmagick', '2.13.2', require: 'RMagick'
# # gem 'rmagick', '2.13.2'
gem 'mini_magick', '3.7.0'

# 手軽に画像がアップロードできる
gem 'paperclip', '4.1.1'

# 日本語処理用
gem 'rails-i18n', '4.0.2'

# seo
gem 'sitemap_generator', '5.0.4'
gem 'meta-tags', :require => 'meta_tags'

# google analytics用
gem 'garb', '0.9.8'

# # bootstrap用
gem 'bootstrap-datepicker-rails', '1.3.0.2'
gem 'flatui-rails', '0.0.4'
# # gem 'twitter-bootstrap-rails', '2.2.8'
# # gem 'bootstrap-sass', '2.3.2.0'

# 定期的な動作用
gem 'sidekiq', '2.16.1'
gem 'redis', '3.0.7'

# erbを楽に書くためのテンプレートエンジン
gem 'slim', '2.0.2'
gem 'slim-rails', '2.1.4'

# # htmlからの抽出用
# gem 'nokogiri', '1.6.2.1'

# # htmlタグ抽出用
# gem 'sanitize', '2.1.0'

# # ページネーター
# gem 'kaminari', "0.16.1"

# 設定ファイル用
gem 'settingslogic', '2.0.9'

# 文字コード変換用ライブラリ
# gem 'iconv', '1.0.4'

# crontab管理ライブラリ、定期実行するような処理がある場合は検討
gem 'whenever', '0.9.2'

# エラー通知
gem 'exception_notification', '4.0.1'

# #tutorial用
# gem 'turbolinks', '1.1.1'

# #password用
# gem 'sprockets', '2.11.0'
# gem 'bcrypt-ruby', '3.1.2'

#font用
gem "font-awesome-rails", "4.1.0.0"

# 都道府県のDB登録を省くよう
gem 'jp_prefecture'

# heroku
gem 'rails_12factor', group: :production

# 論理削除
gem 'kakurenbo'

# 開発環境用
group :development do
  gem 'libv8'
  gem 'rspec-rails', '2.13.1'
  # モデル関係図を自動で出してくれる
  gem 'rails-erd', '1.1.0'
  gem 'pry-rails', '0.3.2'
  gem 'pry-doc', '0.6.0'
  gem 'meta_request', '0.3.0'
  gem 'bullet', '4.10.0'
  gem 'rack-mini-profiler', '0.9.1'
  # エラー画面をわかりやすく
  gem 'better_errors', '1.1.0'
  gem 'sqlite3', "1.3.8"
  # gem 'binding_of_caller', '0.7.2'

  # capistrano
  gem 'capistrano'
  gem 'capistrano-ext' # 環境毎に設定を変更するためのgem
  gem 'capistrano_colors' # capistrano実行時に色をつけるためのgem
  gem 'rvm-capistrano' # rbenvの設定をするため
  gem 'capistrano_database_yml' # database.ymlを使うため
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails', '4.0.1'
  gem 'uglifier', '2.5.1'
  gem 'less-rails'
  gem 'therubyracer', :platforms => :ruby
end

group :test do
  gem 'factory_girl_rails', '4.2.1'

end