source 'https://rubygems.org'

ruby_is_less_22 = Gem::Version.new(RUBY_VERSION) < Gem::Version.new('2.2.0')

if ruby_is_less_22
  gem 'rails', '>= 4.0.0.rc1', '< 4.2.0.rc1'
else
  gem 'rails', '~> 4.2'
end

# Specify your gem's dependencies in migration_data.gemspec
gemspec
