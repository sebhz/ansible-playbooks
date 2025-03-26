# ansible-playbooks
Fun with ansible

## Inventory
Check inventory file

## Deployment
- Deploy headless setup: `ansible-playbook playbooks/headless.yaml [--tags tag1,tag2] [--limit group] [--ask-become-pass] [--ask-pass]`
- Deploy desktop setup: `ansible-playbook playbooks/desktop.yaml [--tags tag1,tag2] [--limit group] [--ask-become-pass] [--ask-pass]`

### Available tags
xscreensaver_tag, filen_tag
