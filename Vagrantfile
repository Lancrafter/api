# -*- mode: ruby -*-
# vi: set ft=ruby :

require 'json'
require 'yaml'

configFile = File.expand_path("./vagrant/config.yaml")
require_relative 'vagrant/setup.rb'

Vagrant.configure(2) do |config|

  Build.configure(config, YAML::load(File.read(configFile)))

end