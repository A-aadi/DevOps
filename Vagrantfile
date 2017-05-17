Vagrant.configure("2") do |config|
  config.vm.box = "centos6.7"
  config.vm.network "forwarded_port", guest: 22, host: 2201
  config.vm.network "forwarded_port", guest: 8153, host: 9152
  config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
     vb.cpus = 1
  end
  config.vm.network "private_network", ip: "192.168.33.10"
end
