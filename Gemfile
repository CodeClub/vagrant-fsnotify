source 'https://rubygems.org'

# Set correct Ruby version before bundle
ruby File.read(File.join(File.expand_path('~'), ".ruby-version"))

group :development do
  gem "vagrant", git: "https://github.com/mitchellh/vagrant.git", ref: 'v1.7.3'
end

group :plugins do
  gem "vagrant-fsnotify", path: "."
end
