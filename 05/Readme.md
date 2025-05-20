```bash
rakibulh@ubuntu-controller:~/ansible_kb/05$ ansible-playbook fifth-playbook.yaml

PLAY [all] *******************************************************************************************

TASK [web_servers : create user simone into the managed nodes] ***************************************
ok: [target1]
ok: [target2]

TASK [web_servers : add ssh key for simone on the managed nodes] *************************************
ok: [target1]
ok: [target2]

TASK [web_servers : add sudoers file for simone] *****************************************************
ok: [target2]
ok: [target1]

PLAY RECAP *******************************************************************************************
target1                    : ok=3    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
target2                    : ok=3    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0

```