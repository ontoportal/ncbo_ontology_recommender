source 'https://rubygems.org'

gem 'oj', '~> 3.0'
gem 'rake'
gem 'request_store'
gem 'parallel'
gem 'json-ld'
gem 'jwt'

# NCBO
gem 'goo', github: 'ontoportal/goo', branch: 'master'
gem 'ncbo_annotator', github: 'ontoportal/ncbo_annotator', branch: 'master'
gem 'ontologies_linked_data', github: 'agroportal/ontologies_linked_data', branch: 'master'

# agroportal ontologies_linked_data requires net/ftp, a bundled gem since Ruby 3.1
gem 'net-ftp'

group :development do
  gem 'ontoportal_testkit', github: 'ontoportal/ontoportal_testkit', branch: 'main'
  gem 'minitest'
  gem 'pry'
  gem 'simplecov'
  gem 'simplecov-cobertura' # for codecov.io
end
