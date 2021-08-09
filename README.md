# ansible-setup-k8s-cluster
its a simple ansible role base playbook file for setup a k8s cluster.<br/> 
remember: unfortunately its just work on ubuntu,debian servers :)
# how can use
# 1- install ansible
sudo apt update

sudo apt install software-properties-common

sudo apt-add-repository --yes --update ppa:ansible/ansible

sudo apt install ansible


# 2- Run playbook 
### Notify that You must modify variables and hosts in hosts file.<br/>

ansible-playbook site.yml -i hosts
