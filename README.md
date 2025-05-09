# Deploy DUO for SSH

## Note: See extra/README.md 
If you want to first add a user that can bypass duo for future playbook runs  
If you change the username from ansible, make sure you add it to groups with !username

## To install
* Edit hosts file or use your own
* Edit vars/vars.yml and set your information from DUO Application Unix
* Additional settings can be set by editing templates/pam_duo.conf.j2 See: https://duo.com/docs/loginduo#duo-configuration-options
* ansible-playbook -i hosts tasks/main.yml

## Change Log
5/8/2025 - Bump for 24.04  
11/7/2023 - Verified working on DO and Azure  
11/4/2023 - Initial creation  


## Sometimes the lie is easier to live with ~ Tom