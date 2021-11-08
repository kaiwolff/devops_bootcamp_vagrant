# Vagrant

Vagrant is a means of automating the setup of virtual machines. The instructions are saved in a vagrantfile. Through this method, it is possible to ensure everyone can run software in the same environment.


![](images/dev-env.png)

## Vagrantfiles

These can be updated, but to apply the changes to the virtual machine, it is necessary to use ```vagrant reload```, or to destroy and rebuild the virtual machine.

### Automating Provisioning

This is done in order to package all requirements associated with a project.

This is done via a shell script on the virtual machine