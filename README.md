[![License](https://ansible.l3d.space/svg/l3d.linux_license_collection.svg)](LICENSE)

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

## Collection
This role is part of the l3d.linux collection.
 + [![collection l3d.linux](https://ansible.l3d.space/svg/l3d.linux_ansible-collection_collection.svg)](https://galaxy.ansible.com/ui/repo/published/l3d/linux/)
 + [![l3d.linux.resolvconf](https://ansible.l3d.space/svg/l3d.linux.resolvconf_ansible-role.svg)](https://github.com/roles-ansible/ansible_role_resolvconf.git)
