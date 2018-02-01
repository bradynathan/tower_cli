# README.md
# Ansible Role: tower-cli

An Ansible role that installs tower-cli on EL/Centos 7.x

## Requirements

tower-cli requires python and will use pip to install dependencies.

## Role Variables

Available variables are listed below, along with default values:

*  tower_host: localhost
*  tower_username: admin
*  tower_password: _no default_


## Dependencies

none

## Example Playbook

    - hosts: all
      vars:
        tower_host: tower.example.com
        tower_username: admin
        tower_password: 'dRV9CKo67sV6DKS8it'
      roles:
        - tower_cli

## License

GPLv4
