require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "jetty"

    gem.summary = %Q{A JavaGem version of Jetty Server - packaged by JavaGems (http://www.javagems.org) - original by Mort Bay Consulting (http://www.mortbay.com)}



    gem.description = "Jetty server core"    

    gem.homepage = "http://www.javagems.org/"

    gem.authors = ["pending/unknown"]

    gem.email = "autobuild@javagems.org"
    gem.version = "6.1.22"

  

    gem.add_development_dependency "junit", "~>3.8.2"

    gem.add_development_dependency "jetty-util", "~>6.1.22"

    gem.add_development_dependency "servlet-api", "~>2.5"

  end
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

task :default => :build
