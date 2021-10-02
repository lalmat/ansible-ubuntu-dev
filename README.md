# Ansible Playbook - Lalmat's Ubuntu Web Development Tools

This playbook install my prefered tools available under Ubuntu.

## Stuff
- [Docker](https://www.docker.com/)
- [GitFlow](https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow) & `git-deploy` alias - assuming you're using GitLab
- Laravel `artisan` alias
- [PHP 8.0](https://www.gnome.org/) & [Composer](https://getcomposer.org/) - using Ondrej PPA
- [NodeJS](https://nodejs.org/en/) - v14 LTS
- [Visual Studio Code](https://code.visualstudio.com/) - as main IDE
- [Sublime Text](https://www.sublimetext.com/) - as secondary Editor

## Requirements

You need to have theses packages already installed (use apt to install them) :
- zsh
- git
- ansible
- software-properties-common

## Installation

Just run this command :

`sudo ansible-pull -U https://github.com/lalmat/ansible-ubuntu-dev.git`

Done.