# Red Hat® Ansible® for install and uninstall Visual Studio Code.
IT Automation with Red Hat® Ansible®!

#### Change username in variables field
```Shell
 vars:
    ## User name
    USER: u987891158
```

#### Install or uninstall VSC app.
```Shell
sudo ansible-playbook setupVisualStudioCode.yml --tags install

OR

sudo ansible-playbook setupVisualStudioCode.yml --tags uninstall

