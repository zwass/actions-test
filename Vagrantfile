Vagrant.configure("2") do |config|
  config.vm.box = "cloud-image/ubuntu-22.04"
  config.vm.box_version = "20260218.0.0"

config.vm.provider "libvirt" do |lv|
    lv.machine_type = "pc"
    lv.driver = "qemu"
    lv.cpu_mode = "custom"
    lv.cpu_model = "qemu64"
    lv.cpus = 16
    lv.memory = 16384
end
end