source 'https://rubygems.org'

# Since I'm following a tutorial strictly and would like to have the same output as the tutorial,
# I decided to use the exact version as stated in the tutorial to prevent errors and confustion
# later in the tutorials. Hopefully this decision will greatly improve my understanding.
# Previously, the default code uses symbols such as ">=" and "~>" which would have the latest
# version of the gem installed. Explanation on the two symbols can be found here:
# Below listing 1.4 at https://www.railstutorial.org/book/beginning

#so if I change something here

gem 'rails',        '5.1.4'
gem 'puma',         '3.9.1'
gem 'sass-rails',   '5.0.6'
gem 'uglifier',     '3.2.0'
gem 'coffee-rails', '4.2.2'
gem 'jquery-rails', '4.3.1'
gem 'turbolinks',   '5.0.1'
gem 'jbuilder',     '2.7.0'

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug',  '9.0.6', platform: :mri
end

group :development do
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

group :production do
  gem 'pg', '0.20.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
