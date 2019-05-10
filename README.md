how to setup python3.6 with tools ansible

vim /etc/ansible/hosts

add text below:

[server3]
server-prometheus-3 ansible_host=192.168.1.179 ansible_port=22 ansible_user=root ansible_ssh_pass=nntai@tainguyenbp

run playbook:

ansible-playbook install.yml
