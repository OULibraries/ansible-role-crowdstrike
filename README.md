OULibraries.crowdstrike
=========

An ansible role for deploying the CrowdStrike sensor to Red-Hat based systems.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

Usage of this role requires the `crowdstrike_cid` variable to be provided. The variables refers to the customer ID used to associate the Linux system with the appropriate customer dashboard.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - role: OULibraries.crowdstrike 

License
-------

[MIT](https://github.com/OULibraries/ansible-role-crowdstrike/blob/main/LICENSE)

Author Information
------------------

James Mitchell
