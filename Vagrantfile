Vagrant.configure("2") do |config|
  config.vm.box = "cloud-image/ubuntu-22.04"

  config.vm.provider "libvirt" do |lv|
    lv.machine_type = "pc"
    lv.driver = "qemu"
    lv.cpu_mode = "custom"
    lv.cpu_model = "qemu64"
    lv.cpus = 16
    lv.memory = 16384
    lv.qemu_use_session = false
    lv.management_network_address = "192.168.121.0/24"
  end
end