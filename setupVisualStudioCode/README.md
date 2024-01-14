# Red Hat® Ansible® for install and uninstall Visual Studio Code.
IT Automation with Red Hat® Ansible®!


#### Install or uninstall VSC app.
```Shell
sudo ansible-playbook setupVisualStudioCode.yml --tags=install

OR

sudo ansible-playbook setupVisualStudioCode.yml --tags=uninstall

