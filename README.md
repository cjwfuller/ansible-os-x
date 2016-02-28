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

## Apps

You can modify the OS X apps that are installed by changing the cask list in `roles/base_osx/defaults/main.yml`:

```
casks:
  ...
  - skype
  - slack
  - vlc
  - flux
  ...
```

## Packages

You can modify other packages e.g. `zsh` that are installed by changing the package list in `roles/base_osx/defaults/main.yml`:

```
packages:
  ...
  - node
  - wget
  - zsh
  ...
```

## Applying Changes

To apply changes to your Ansible configuration, re-run Ansible: `ansible-playbook main.yml -i hosts --ask-sudo-pass`
