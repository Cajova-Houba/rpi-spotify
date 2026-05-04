# About

Ansible configuration for setting up spotify on clean RPI installation.

# RPI hole

192.168.0.10
B8:27:EB:E7:70:18

```bash
 ansible-playbook --vault-password-file path/to/pwd_env -i inventories/home playbooks/install-pihole.yml 
```

# brscan troubleshooting

```bash
# Check USB detection
brsaneconfig4 -d

# Check brscan-skey status
brscan-skey -l

# Restart the Scan Key Tool
brscan-skey
```