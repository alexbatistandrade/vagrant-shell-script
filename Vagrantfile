Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.hostname = "vagrant-nginx"
  config.vm.network "public_network"
  config.vm.provision "shell",
    path: "script.sh"

  config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
     vb.cpus ="2"

  end
end