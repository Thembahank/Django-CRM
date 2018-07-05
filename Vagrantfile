# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-16.04"
  config.vm.network "forwarded_port", guest: 8000, host: 8008, host_ip: "127.0.0.1"  # Django runserver
  config.vm.network "forwarded_port", guest: 8000, host: 8008, host_ip: "127.0.0.1"  # Django runserver
  config.ssh.forward_agent = true
  config.ssh.password = false
end
