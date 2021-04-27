source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'
gem 'rails', '~> 6.1.3', '>= 6.1.3.1'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'active_model_serializers'  # JSONシリアライザ
gem 'rails-i18n'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'       # Rails用のテストフレームワーク 
  gem 'factory_bot_rails' # テストデータ作成用
  gem 'faker'             # ダミーデータの生成
  gem 'pry-byebug'
  gem 'pry-doc'
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
