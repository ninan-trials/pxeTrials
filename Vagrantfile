Vagrant.configure("2") do |config|

  # create mgmt node
  config.vm.define :mgmt do |mgmt_config|
      mgmt_config.vm.box = "ubuntu/trusty64"
      mgmt_config.vm.hostname = "mgmt"
      mgmt_config.vm.network :public_network, ip: "10.0.15.10"
      mgmt_config.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
      end
  end
end
