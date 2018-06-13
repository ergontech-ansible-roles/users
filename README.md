users Role
=========


Role Variables
--------------

```
install_deploy_user: false
users: false

# OR

users:
  - name: some-user
    groups:
      - some-group
    ssh_keys:
      - https://github.com/some-user.keys

deploy_group: deploy
deploy_user: deploy
```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/users-role
#   version: master
#   name: users
```

License
-------

[MIT](LICENSE)