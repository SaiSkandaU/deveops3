- name: Experiment 7 - Run Task on Localhost
  hosts: local
  tasks:
    - name: Print Hello
      debug:
        msg: "Hello from Ansible on Windows via WSL!"


Ansible - i inventory local  -m ping

ansible-playbook -i inventory playbook.yml
