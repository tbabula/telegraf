telegraf role forked from dj-wabasi/ansible-telegraf with custom extension to support monitoring bare metal power monitoring

Added the following changes to the ansible-telegraf-role:

+freeipmi.yml - Installs FREEIPMI package on RHEL distribution systems

+main.yml - added lines for executing freeipmi.yml and telegraf.yml playbook

+telegraf.yml - granting telegraf user account sudo priviliges to execute commands in shell without password

+inventory.yml - inventory variables with telegraf monitoring plugins
