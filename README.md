# ansible-os-x

## Installation

Before running the playbook:

Install command line tools: `xcode-select --install`

Install brew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Clone this repo: `git clone git@github.com:cjwfuller/ansible-os-x.git`

`cd ansible-os-x`


Run the playbook: `ansible-playbook main.yml -i inventory --ask-sudo-pass`

