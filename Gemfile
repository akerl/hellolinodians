path = File.dirname(ENV['BUNDLE_GEMFILE'] || '.')
ruby File.read(File.join(path, '.circle-ruby')).chomp
source 'https://rubygems.org'

gem 'indefinite_article', '~> 0.2.0'
gem 'linodians', '~> 1.1.1'
gem 'redis', '~> 4.1.0'
gem 'twitter', '~> 6.2.0'

group :development do
  gem 'codecov', '~> 0.1.1'
  gem 'fuubar', '~> 2.4.1'
  gem 'goodcop', '~> 0.7.1'
  gem 'rake', '~> 13.0.0'
  gem 'rspec', '~> 3.9.0'
  gem 'rubocop', '~> 0.76.0'
end
