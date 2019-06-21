# moodle_deploy


## Deployment


To deploy the Moodle please spceify the IP in `inventory.ini` and ssh key file path in `ansible.cfg` then run following command from `ansible` directory:


```
ansible-playbook -i inventory.ini moodle.yaml
```

After successfull passing the ansible tasks you will be able to get Moodle page on `http://SPECIFIED_IP` link
