source 'https://rubygems.org'

# Specify your gem's dependencies in ansible_spec.gemspec
gemspec

if Gem::Version.new(RUBY_VERSION.dup) < Gem::Version.new('2.0.0')
  # net-ssh 3.x dropped Ruby 1.8 and 1.9 support.
  gem 'net-ssh', '~> 2.7'
end

if Gem::Version.new(RUBY_VERSION.dup) <= Gem::Version.new('1.9.3')
  gem 'json', '~> 1.8.3'
end
