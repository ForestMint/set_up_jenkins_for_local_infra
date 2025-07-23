Vagrant.configure("2") do |config|
  config.vm.provider :libvirt do |libvirt|
    libvirt.cpus = 4
    libvirt.cpuset = '1-4,^3,6'
    libvirt.cputopology :sockets => '2', :cores => '2', :threads => '1'
  end
end

