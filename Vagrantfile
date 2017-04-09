# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "consul1" do |consul1|
    consul1.vm.box = "centos/7"
    consul1.vm.network "public_network", ip: "10.10.10.141"
    consul1.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
    end
  end
end