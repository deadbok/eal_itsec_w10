# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
    config.vm.define "aserver" do |aserver|
      aserver.vm.box = "debian/jessie64"
       config.vm.network "public_network"
    end

    config.vm.define "aclient" do |aclient|
      aclient.vm.box = "debian/jessie64"
       config.vm.network "public_network"
    end
end
