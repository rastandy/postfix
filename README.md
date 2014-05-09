postfix
========

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/postfix/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/postfix)

A role to install and configure postfix.

Requirements
------------

No external requirements.

Role Variables
--------------

* `postfix_relayhost`: "smtp.mailgun.org"
* `postfix_relayhost_port`: "587"
* `postfix_sasl_user`: "postmaster"
* `postfix_sasl_domain`: "mydomain.com"
* `postfix_sasl_password`: "password"
* `postfix_tls_support`: "no"

Dependencies
------------

No dependencies.

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: Rackspace_Automation.postfix, x: 42 }

License
-------

BSD

Author Information
------------------

[Rackspace - the open cloud company](http://rackspace.com)

Ask about our DevOps Automation Service - [www.rackspace.com/devops](http://rackspace.com/devops)
