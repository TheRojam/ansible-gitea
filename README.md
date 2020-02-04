# ROLE _TEMPLATE

A brief description of the role goes here.


## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role
should be mentioned here. For instance, if the role uses the EC2 module, it
may be a good idea to mention in this section that the boto package is required.


## Role Variables

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.)
should be mentioned here as well.


## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables
that are used from other roles.


## Example Playbook


Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

```
  - hosts: servers
    roles:
       - { role: _role-name }
```
## Tips / Scripts

### script to clone tmple into new role
there are some scripts that you can use to create a fresh role from this template
to create a fresh role and cloning this repo just use
tmpl2role.sh <rolename>
```
$ sh -c "$(wget https://gogs.sportresult.com/itsdeploy/admin-scripts/raw/new-scripts/tmpl2role.sh -O -) <rolename>"
```
### script to change tmpl afte cloning into new role

if you have already downloaded this tmpl just use
change-tmpl2role.sh <rolename>
```
$ sh -c "$(wget https://gogs.sportresult.com/itsdeploy/admin-scripts/raw/new-script/change-tmpl2role.sh -O -) <rolename>"
```


## License

SGS - internal use


## Author Information

Role was written by:

* SGS

