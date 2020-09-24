Vagrant.configure("2") do |config|
  
  config.vm.define "docker1" do |docker1|
    docker1.vm.box = "ubuntu/xenial64"
    docker1.vm.hostname = "docker1.local"
    docker1.vm.network "private_network", ip: "192.168.50.130"

    docker1.vm.provider "virtualbox" do |v|
        v.memory = 4096
        v.cpus = 4
    end
    docker1.vm.provision :ansible_local do |ansible|
      ansible.playbook = "/vagrant/provisioning/docker-install.yml"
    end
    
  end
end