PROVISIONING_PATH = "/vagrant_data"

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.hostname = "ansible-lab"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.synced_folder "./playbooks", PROVISIONING_PATH

  config.vm.provider "virtualbox" do |vb|
    vb.name = "ansible-lab"
    vb.cpus = "2"
    vb.memory = "3072"
  end

  config.vm.provision "ansible_local" do |ansible|
    ansible.provisioning_path = PROVISIONING_PATH
    ansible.playbook = "playbook.yml"
    ansible.install = true
  end
end