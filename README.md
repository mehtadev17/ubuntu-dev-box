# ubuntu-dev-box

# Run Locally: 
Note: Works on Ubuntu 1604
```
sudo su #Type in password when prompted and hit enter
ansible-playbook provisioners/playbook.yml -i host_vars/dev_host --connection=local
exit
```

# Run Vagrantbox:
Note: vagrantbox is on trusty32

```
vagrant up --provision
```