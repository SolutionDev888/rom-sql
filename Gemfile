source 'https://rubygems.org'

gemspec

gem 'dry-types', github: 'dry-rb/dry-types', branch: 'master'
gem 'rom', github: 'rom-rb/rom', branch: 'add-explicit-relation-name'
gem 'rom-support', github: 'rom-rb/rom-support', branch: 'call-to_sym'

group :test do
  gem 'byebug', platforms: :mri
  gem 'anima', '~> 0.2.0'
  gem 'virtus'
  gem 'activesupport'
  gem 'rspec', '~> 3.1'
  gem 'codeclimate-test-reporter', require: false
  gem 'pg', platforms: [:mri, :rbx]
  gem 'jdbc-postgres', platforms: :jruby
  gem 'sqlite3', platforms: [:mri, :rbx]
  gem 'jdbc-sqlite3', platforms: :jruby
end

group :tools do
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-rubocop'
  gem 'rubocop', '~> 0.28'
end
