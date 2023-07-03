
# Example of setting a Conda environment

## Introduction

Use this playbook to create an Conda environment

## Setup

Install this requirements:

```bash
sudo dnf install ansible
ansible-galaxy role install -r roles/requirements.yml
```

## Usage (VM)


Take note of the hostname or IP Address of the server and run the playbook, for ex:

```bash
ansible-playbook --user root --inventory 192.168.122.164, playbook.yml
```

