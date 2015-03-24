# -*- mode: ruby -*-

Vagrant.configure(2) do |config|
  config.vm.box = "hashicorp/precise32"

  config.vm.provision :shell, :path => "install-rvm.sh",  :args => "stable"
  config.vm.provision :shell, :path => "install-ruby.sh", :args => "1.9.3"
  config.vm.provision :shell, :path => "install-ruby.sh", :args => "2.0.0 rails haml"
end
