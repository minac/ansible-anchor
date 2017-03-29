# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "debian/jessie64"
  config.vm.hostname = "anchor"
  config.vm.network :forwarded_port, guest: 80, host: 8080, id: "http"
  config.vm.post_up_message = "Welcome to your brand new Anchor CMS at #{config.vm.hostname}\nAre you ready to work?\nvagrant ssh"    

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "tests/test.yml"
    ansible.verbose = true
  end
end

