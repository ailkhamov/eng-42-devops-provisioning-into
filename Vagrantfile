
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip: "192.168.10.100"
  config.hostsupdater.aliases = ["abror.local"]

  # synced app folder
  config.vm.synced_folder "app", "/app"
  config.vm.provision "shell", inline: <<SHELL
    sudo apt-get update
    sudo apt-get install -y nginx
SHELL
  #config.vm.provision "shell", path: "enviroment/provision.sh"

end
