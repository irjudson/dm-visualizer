source 'https://rubygems.org'

group(:runtime) do
  gem 'ruby-graphviz',	'>= 0.9.10'
  gem 'dm-core',	'>= 0.10.2'
  gem 'thor',		'>= 0.13.4'
end

group(:development) do
  gem 'rake',			'~> 0.8.7'
  gem 'jeweler',		'~> 1.4.0', :git => 'git://github.com/technicalpickles/jeweler.git'
end

group(:doc) do
  case RUBY_PLATFORM
  when 'java'
    gem 'maruku',	'~> 0.6.0'
  else
    gem 'rdiscount',	'~> 1.6.3'
  end

  gem 'yard',			'~> 0.5.3'
end

gem 'rspec',	'~> 1.3.0', :group => [:development, :test]
