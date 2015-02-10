Adama deployer
==============

Deploy Adama distributed system using
[serfnode-deployer](http://github.com/waltermoreira/serfnode-deployer).

Quickstart
----------

- Pull or install [serfnode-deployer](http://github.com/waltermoreira/serfnode-deployer)

- Define your list of hosts (see `hosts.example`) and access methods

- Tweak variables: `{host,group}_vars`

- Tweak playbook: `play.yml`

- Deploy:
  ```
  $ serfnode-deployer play.yml
  ```
