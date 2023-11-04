# Deploy DUO for SSH

Only Supporting Ubuntu 22.04 for the moment

# To install
* Edit hosts file or use your own
* Edit vars/vars.yml and set your information from DUO Application Unix
* Additional settings can be set by editing templates/pam_duo.conf.j2 See: https://duo.com/docs/loginduo#duo-configuration-options
* ansible-playbook -i hosts tasks/main.yml

# Change Log
11/4/2023 - Initial creation


# Sometimes the lie is easier to live with ~ Tom