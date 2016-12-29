Vagrant.configure("2") do |config|
  config.vm.box = "oriole"
  config.vm.box_check_update = false
  config.ssh.username = "ubuntu"
  config.ssh.password = "oriole"
  config.ssh.insert_key = false
  config.vm.network "forwarded_port", guest: 6379, host: 6379
  config.vm.network "forwarded_port", guest: 27017, host: 27017
  config.vm.network "forwarded_port", guest: 5672, host: 5672
  config.vm.network "forwarded_port", guest: 3306, host: 3306
end