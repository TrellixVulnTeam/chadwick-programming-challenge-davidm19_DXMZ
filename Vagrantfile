Vagrant.configure("2") do |config|
  config.vm.box = "voterlabs/programming-challenge"
  config.vm.provider "virtualbox" do |vb|
    vb.customize [ "modifyvm", :id, "--uartmode1", "disconnected" ]
  end
end
