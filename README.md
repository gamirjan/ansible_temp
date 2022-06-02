## Wordpress on Ubuntu 20
We are using ansible to deploy wordpress, mysql and nginx.


>ansible_ssh_host=[your_ip]
>
>ansible_ssh_user=[your_username]
>
>ansible_ssh_private_key_file=[your_ssh_private_key_path]

### To check syntax run:

>ansible-playbook main.yml --syntax-check

### To deploy wordpress run:

>ansible-playbook main.ym

