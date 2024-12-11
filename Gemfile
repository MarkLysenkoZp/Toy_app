source 'https://rubygems.org'

gem 'rails', '4.2.11.3'
gem 'sass-rails',           '5.0.6'   # Обновлено для лучшей совместимости
gem 'uglifier',             '4.2.0'   # Современная версия Uglifier
gem 'coffee-rails',         '4.1.1'   # Последняя совместимая версия
gem 'jquery-rails',         '4.0.5'   # Обновлено для устранения багов
gem 'turbolinks',           '2.5.3'   # Совместимая версия
gem 'jbuilder',             '2.4.1'   # Более стабильная версия
gem 'sdoc',                 '0.4.1', group: :doc # Обновлённый SDoc

group :development, :test do
  gem 'sqlite3',     '1.3.13' # Исправлены ошибки совместимости
  gem 'byebug',      '9.0.6'  # Современная версия
  gem 'web-console', '2.3.0'  # Совместимая версия
  gem 'spring',      '1.3.6'  # Улучшенная стабильность
  gem 'ffi', '1.12.2'
end

group :production do
  gem 'pg', '0.18.4' # PostgreSQL для развертывания на Heroku
  gem 'rails_12factor', '0.0.3' # Необходим для работы на Heroku
end