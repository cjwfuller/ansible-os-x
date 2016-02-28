# ansible-os-x

Provision a local OS X dev machine using Ansible

## Installation

Ensure XCode command-line tools are installed:

* `xcode-select --install`

Install brew package manager:

* `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Install Ansible:

* `brew install ansible`

Clone this repo:

* `git clone https://github.com/cjwfuller/ansible-os-x.git`

* `cd ansible-os-x`

Run playbook:

* `ansible-playbook main.yml -i hosts --ask-sudo-pass`
