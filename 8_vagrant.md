Installations


Vagrantfile

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
end

Commands:
vagrant init
vagrant up
vagrant ssh
exit
vagrant box list

vagrant suspend
vagrant resume
vagrant halt
vagrant destroy


