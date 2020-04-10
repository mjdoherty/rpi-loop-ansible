# rpi-loop-ansible
Create ext4 filesystem on /dev/loop0

# Verify the ansible inventory 

```
    ansible -i inventory all -m ping
```

# Run the ansible playbook

```
    ansible-playbook -i inventory -v site.yaml
```


