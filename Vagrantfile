VAGRANTFILE_API_VERSION ||= "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.provision "shell", path: "~/vagrantfiles/provision"
  config.vm.provision "shell", path: "~/vagrantfiles/user-provision", privileged: false
  config.ssh.forward_agent = true
end
