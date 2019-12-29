Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.network "public_network",
  use_dhcp_assigned_default_route: true
  
	config.vm.provider "virtualbox" do |v|
		v.memory = 3072
		v.cpus = 2
	end
end
