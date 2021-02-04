# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"

  config.vm.provision :shell, path: "./setup.sh"

  config.vm.network "forwarded_port", guest: 443, host: 4444
end
