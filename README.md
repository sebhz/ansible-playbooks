# ansible-playbooks
Fun with ansible

## Inventory
Check inventory file

## Deployment
- Deploy headless setup: `ansible-playbook playbooks/headless.yaml [--limit group] [--ask-become-pass] [--ask-pass]`
- Deploy desktop setup: `ansible-playbook playbooks/desktop.yaml [--limit group] [--ask-become-pass] [--ask-pass]`
