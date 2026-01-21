Vagrant.configure("2") do |config|
  config.vm.box = "debian/bullseye64"

  config.vm.network "forwarded_port", guest: 8000, host: 8000

  config.vm.hostname = "flask-bullseye"
end
