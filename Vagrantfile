Vagrant.configure("2") do |config|
  config.vm.box = "quent01/vm-starter--lamp"
  config.vm.synced_folder "src/",  "/srv/scripts"
  config.vm.network "forwarded_port", guest: 8000,  host: 8000
end
