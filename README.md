# Getting Started
```
vagrant up  
vagrant ssh-config --host apache-test-01 >> ~/.ssh/config
ansible-playbook -i hosts playbook.yml
```

## Reboot Server
```
shutdown -r now
```

## Synbolic Link Local 2 Vagrant Command
```
sudo rm -rf /var/www/html   
sudo ln -fs /vagrant /var/www/html
```

## Sync Local 2 Vagrant
```
vagrant rsync-auto
```
