[![Ansible Galaxy](https://raw.githubusercontent.com/roles-ansible/ansible_role_resolvconf/main/.github/galaxy.svg?sanitize=true)](https://galaxy.ansible.com/do1jlr/resolvconf) [![MIT License](https://raw.githubusercontent.com/roles-ansible/ansible_role_resolvconf/main/.github/license.svg?sanitize=true)](https://github.com/roles-ansible/ansible_role_resolvconf/blob/main/LICENSE)

 ansible role resolvconf
=========================

Ansible role to manage the ``/etc/resolv.conf`` file.

 Variables
-------------
| Variable | Default Value | Description |
| -------- | ------------- | ----------- |
| ``resolvconf__mode:`` | ``'0644'`` | The file mode for ``/etc/resolv.conf`` |
| ``resolveconf__immutable:`` | ``false`` | Change this to ``true`` to prevent ``/etc/resolv.conf`` to be changed by others |
| ``resolvconf__nameservers: []`` | `` `` | Optionally configure a list of nameservers *(some [examples](https://www.ccc.de/censorship/dns-howto/))* |
| ``resolvconf__domain:`` | `` `` | Optionally set a value for the domain option |
| ``resolvconf__search: []`` | `` `` | Optionally set a list of search domains |
| ``resolvconf__options: []`` | `` `` | Optionally set a list of additional options like ``rotate`` or ``timeout:2`` |
| ``submodules_versioncheck:`` | ``false`` | Run optional simple Versionscheck *(``true`` is recomended)* |

 Testing
----------
This role is tested with [these github-action](https://github.com/search?q=topic%3Acheck-ansible+topic%3Agithub-actions+org%3Aroles-ansible&type=Repositories) tests for different versions of differen linux systems. Linting is tested via travis-ci and the  [ansible-lint action](https://github.com/marketplace/actions/ansible-lint).
If you want to find out more about our tests, please have a look at the github marketplace.

| test status | Github Marketplace |
| :---------  | :----------------  |
| [![Ansible Lint check](https://github.com/roles-ansible/ansible_role_resolvconf/actions/workflows/ansible-linting-check.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_resolvconf/actions/workflows/ansible-linting-check.yml) | [ansible-lint action](https://github.com/marketplace/actions/ansible-lint) |
| [![Yamllint GitHub Actions](https://github.com/roles-ansible/ansible_role_resolvconf/actions/workflows/yamllint.yaml/badge.svg)](https://github.com/roles-ansible/ansible_role_resolvconf/actions/workflows/yamllint.yaml) |  [yamllint github actions](https://github.com/marketplace/actions/yamllint-github-action) |
| [![Galaxy release](https://github.com/roles-ansible/ansible_role_resolvconf/actions/workflows/galaxy.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_resolvconf/actions/workflows/galaxy.yml) | [publish-ansible-role-to-galaxy](https://github.com/marketplace/actions/publish-ansible-role-to-galaxy) |
