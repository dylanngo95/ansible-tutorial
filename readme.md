
# How to run command
```bash
ansible -i ./hosts all --list-host
ansible -i ./hosts all -m ping
ansible -i ./hosts webserver -b --become-user=root -m shell -a 'apt-get install -y nginx'
```
# Playbox
```bash
State define: reloaded, restarted, started, stopped

ansible-playbook -i ./hosts nginx.yml
```
