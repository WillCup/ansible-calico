will.calico
=========
一个用来部署calico的role，包含下载calicoctl、创建为开机服务两个步骤。

Requirements
------------
None

Role Variables
--------------


See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: will.calico, install_dir: '/server/calico', target_version: '1.6.3' }

License
-------

MIT

Author Information
------------------

runningdata.github.io
