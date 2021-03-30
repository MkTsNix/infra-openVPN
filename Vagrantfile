# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|

 config.vm.box = "centos/7"
   config.vm.define "server" do |server|
   server.vm.hostname = "server.loc"
   server.vm.network "private_network", ip: "192.168.10.10"
 end

 config.vm.define "client" do |client|
   client.vm.hostname = "client.loc"
   client.vm.network "private_network", ip: "192.168.10.20"
 end

 config.vm.define "ras" do |ras|
   ras.vm.hostname = "ras.loc"
   ras.vm.network "private_network", ip: "192.168.10.30"
 end
end