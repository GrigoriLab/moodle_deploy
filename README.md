# moodle_deploy


## To deploy the Moodle please spceify the IP in `inventory.ini` and ssh key file path in `ansible.cfg` then run following command from `ansible` directory:

```
ansible-playbook -i inventory.ini moodle.yaml
```
