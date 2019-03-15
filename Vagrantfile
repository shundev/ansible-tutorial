Vagrant.configure(2) do |config|
  config.vm.define "controller" do |node|
        node.vm.box = "bento/centos-6.7"
        node.vm.hostname = "controller"
        node.vm.network :private_network, ip: "192.168.100.10"
        node.vm.network :forwarded_port, id: "ssh", guest: 22, host: 2210
  end
  config.vm.define "target" do |node|
        node.vm.box = "bento/centos-6.7"
        node.vm.hostname = "target"
        node.vm.network :private_network, ip: "192.168.100.20"
        node.vm.network :forwarded_port, id: "ssh", guest: 22, host: 2220
  end
end
