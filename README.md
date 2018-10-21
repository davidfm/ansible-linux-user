# Ansible Role: Linux User

Small role to create a Linux user.

## Variables

| Variable | Default | Description |
|:--------:|:-------:| ----------- |
|`username`| | Username |
|`passwd` | | Encrypted password | 
|`comment`| |e.g. Full Name|
|`user_groups`| | Needs to be a list `['group1', group2']`...|
|`sudo_permissions` | `False` | |
|`set_passwordless_sudo` | `False` | |
|`generate_ssh_key` |`yes` | |
|`ssh_key_type` | `rsa` | |
|`ssh_key_bits` | `4096` | | 
|`ssh_key_file` | `.ssh/id_rsa` | | 

