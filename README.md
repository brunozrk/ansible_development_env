# Ansible development env

Setup development environment, not completed yet.

## Dependencies

pip:

    sudo apt-get install python-pip

ansible:

    sudo pip install ansible

## Setup

    git clone git@github.com:brunozrk/ansible_development_env.git
    cd ansible_development_env

- edit `vars/defaults.yml` with your preferences.

## Usage

    ansible-playbook playbook.yml --ask-sudo-pass

## License

[MIT license](https://github.com/brunozrk/ansible_development_env/blob/master/LICENSE)
