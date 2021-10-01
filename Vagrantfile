Vagrant.configure(2) do |config|
  config.vm.box = "generic/ubuntu2004"
  
  # Install plugin
  config.vagrant.plugins = "vagrant-docker-compose"
  # install docker and docker-compose
  config.vm.provision :docker
  config.vm.provision :docker_compose
end
