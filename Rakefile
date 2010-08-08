require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "rails_config"
    s.summary = "provides an Settings for rails3 that reads config/settings.yml"
    s.email = "railsjedi@gmail.com"
    s.homepage = "http://github.com/railsjedi/rails_config"
    s.description = "Provides an easy to use Application Configuration object"
    s.authors = ["Jacques Crocker"]
    s.files =  FileList["[A-Z]*", "{bin,generators,lib,spec}/**/*"]

    s.add_development_dependency 'rspec', ">=2.0.0.beta.19"

  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: gem install jeweler"
end