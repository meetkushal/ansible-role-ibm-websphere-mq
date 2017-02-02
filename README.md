IBM Websphere MQ
=====================

[![Build Status](https://travis-ci.org/mm0/ansible-role-ibm-websphere-mq.svg?branch=master)](https://travis-ci.org/mm0/ansible-role-ibm-websphere-mq) [![Galaxy](https://img.shields.io/badge/galaxy-mm0.ibm--websphere--mq-blue.svg?style=flat)](https://galaxy.ansible.com/mm0/ibm-websphere-mq)


An Ansible role that installs IBM Websphere MQ on RHEL/Centos using locally provided installation package and License

Requirements
---------------

- Sudo access
- Locally (on target host) install package available and License 


Role Variables
---------------

Available variables are listed below, there are no defaults:

```yml
```


Dependencies
---------------

None 

Example Playbook
---------------

    - hosts: webservers
            roles:
			- { role: mm0.ibm-websphere-mq }

License
---------------

BSD-2

Author Information
------------------

[Matt Margolin](mailto:matt.margolin@gmail.com)

[mm0](https://github.com/mm0) on github
