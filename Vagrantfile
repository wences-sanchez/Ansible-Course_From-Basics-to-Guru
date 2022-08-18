# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    # Control Node
    config.vm.define "control_node" do |control_node|
        control_node.vbguest.auto_update = false
        control_node.vm.box = "rockylinux/8"
    end

    # Managed nodes
    config.vm.define "rocky" do |rocky|
        rocky.vbguest.auto_update = false
        rocky.vm.box = "rockylinux/8"
    end
    config.vm.define "ubuntu" do |ubuntu|
        ubuntu.vbguest.auto_update = false
        ubuntu.vm.box = "ubuntu/jammy64"
    end
    config.vm.define "windows" do |windows|
        windows.vbguest.auto_update = false
        windows.vm.box = "Microsoft/EdgeOnWindows10"
    end
end
