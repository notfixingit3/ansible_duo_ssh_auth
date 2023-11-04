# Add user to linux that skips DUO Auth

## Why?
Add a user that can run playbooks, until ansible adds duo support

## To install
* Supply a host file
* Edit vars/vars.yml and set your information
* ansible-playbook -i hosts tasks/main.yml

## Change Log
11/4/2023 - Initial creation


## Sometimes the lie is easier to live with ~ Tom