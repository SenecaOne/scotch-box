# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "seneca/box"
  config.vm.network "private_network", ip: "192.168.35.13"
  config.vm.hostname = "senecabox"
  config.vm.synced_folder ".", "/var/www", :mount_options => ["dmode=777", "fmode=666"]

end