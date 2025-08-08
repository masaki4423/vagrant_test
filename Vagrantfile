Vagrant.configure("2") do |config|
  config.vm.box = "castor/proxmox"
  config.vm.box_version = "8.4.0"

  (1..3).each do |i|
    config.vm.define "pve-node#{i}" do |node|
      node.vm.hostname "pve-node#{i}"
    end
  end
end
