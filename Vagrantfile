Vagrant.configure("2") do |config|
	config.vm.box = "bento/ubuntu-22.04"
	config.vm.hostname = "UbuntuVM"
	config.vm.network "private_network", ip: "192.168.56.2"
	config.vm.provider "virtualbox" do |v|
		v.memory = 2048
		v.cpus = 2
	end
end
