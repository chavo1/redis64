# Vagrant box with preinstalled redis64

Prerequisite:

1.  Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2.  Install [Vagrant](https://www.vagrantup.com)
3.  Boot vagrant environment : vagrant init && vagrant up

For more information, visit [Vagrant Documentation](https://docs.vagrantup.com/v2/)

To build vagrant box:

1.  Install [Packer](http://www.packer.io)
2.  Use below command:

packer build <path to xenial64.json file>

To test you will need Kitchen:

For the test you will need Kitchen it is a RubyGem so please find how to install and setup Test Kitchen for developing infrastructure code, check out the [Getting Started Guide](http://kitchen.ci/docs/getting-started/).
