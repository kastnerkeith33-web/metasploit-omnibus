source 'https://rubygems.org'

# Install omnibus
# Pinned to a commit on the r7_9.1.6_custom branch: a Rapid7 fork of omnibus
# 9.1.6 that keeps the license_scout pin avoiding the addressable/public_suffix
# Ruby upgrade. Pinning the commit keeps builds reproducible if the branch moves.
gem 'omnibus', git: 'https://github.com/rapid7/omnibus', ref: 'd2ce429141668d85e6acab845c164220df1c9bae'

# Software definitions live in config/software, not in the omnibus-software gem.

group :development do
  gem 'pry-byebug'
end
