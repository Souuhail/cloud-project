Vagrant.configure("2") do |config|
  config.vm.define "vm1" do |vm1|
    vm1.vm.box = "ubuntu/focal64"
    vm1.vm.network "private_network", ip: "192.168.56.101"
  end

  config.vm.define "vm2" do |vm2|
    vm2.vm.box = "ubuntu/focal64"
    vm2.vm.network "private_network", ip: "192.168.56.102"
  end

  config.vm.define "vm3" do |vm3|
    vm3.vm.box = "ubuntu/focal64"
    vm3.vm.network "private_network", ip: "192.168.56.103"
  end
end

