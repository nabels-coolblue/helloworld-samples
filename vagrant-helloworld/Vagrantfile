# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |v|
    v.memory = 4096
  end
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision "shell", path: "scripts/global.sh"
  config.vm.define "server" do |server|
    server.vm.provision "shell", path: "scripts/server.sh"
    server.vm.hostname = "server"
  end
end