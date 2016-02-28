# ansible-os-x

Provision a local OS X dev machine using Ansible

## Installation

Ensure XCode command-line tools are installed:

1. `xcode-select --install`

Install brew package manager:

2. `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Install Ansible:

3. `brew install ansible`

Clone this repo:

4. `git clone https://github.com/cjwfuller/ansible-os-x.git`

5. `cd ansible-os-x`

Run playbook:

6. `ansible-playbook main.yml -i hosts --ask-sudo-pass`
