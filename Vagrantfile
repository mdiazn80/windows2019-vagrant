Vagrant.configure("2") do |config|
  config.vm.box = "gusztavvargadr/windows-server-2019-standard"
  config.vm.synced_folder "./data", "/vagrant"
  
  config.vbguest.auto_update = false
  config.vbguest.no_remote = true

  config.winssh.shell = "powershell"

  config.vm.provider "virtualbox" do |vb|
      vb.gui = true
      vb.cpus = 4
      vb.memory = "8192"
  end
end