ansible-playbook -i hosts playbook.yml

shutdown -r now

sudo rm -rf /var/www/html
sudo ln -fs /vagrant /var/www/html
