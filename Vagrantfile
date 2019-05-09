Vagrant.configure("2") do |config|

# Configure all of the VirtualBox VMs to use 2G of RAM and 2 CPUs
config.vm.provider "virtualbox" do |v|
  v.memory = 2048
  v.cpus = 2
end

# Create a sample VM
  config.vm.define name="core2" do |node|
    node.vm.box = "alpine/alpine64"
  end

end
