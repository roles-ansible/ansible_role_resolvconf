 ansible role resolvconf
=========================

Ansible role to manage the ``/etc/resolv.conf`` file.

 Variables
-------------
| Variable | Default Value | Description |
| -------- | ------------- | ----------- |
| ``resolvconf__mode:`` | ``'0644'`` | The file mode for ``/etc/resolv.conf`` |
| ``resolveconf__immutable:`` | ``false
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
| [![Ansible Lint check](https://github.com/DO1JLR/ansible_role_resolvconf/workflows/Ansible%20Lint%20check/badge.svg)](https://github.com/DO1JLR/ansible_role_resolvconf/actions?query=workflow%3A%22Ansible+Lint+check%22) | [ansible-lint action](https://github.com/marketplace/actions/ansible-lint) |
| ![Yamllint GitHub Actions](https://github.com/DO1JLR/ansible_role_resolvconf/workflows/Yamllint%20GitHub%20Actions/badge.svg) |  [yamllint gitHub actions](https://github.com/marketplace/actions/yamllint-github-action) |
