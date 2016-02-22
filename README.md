# ansible-os-x

## Installation

Before running the playbook:

Install command line tools: `xcode-select --install`

Install brew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Install ansible: `brew install ansible`

Clone this repo: `git clone https://github.com/cjwfuller/ansible-os-x.git`

`cd ansible-os-x`


Run the playbook: `ansible-playbook main.yml -i hosts --ask-sudo-pass`

