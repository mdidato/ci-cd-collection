automation_bootcamp.my_collection hello_world Role
========================

A simple 'Hello, World' role.

Requirements
------------

N/A

Role Variables
--------------

N/A

Dependencies
------------

N/A


Example Playbook
----------------

```yaml
- name: Execute hello_world role
  hosts: all
  roles:
    - role: automation_bootcamp.my_collection.hello_world 
```

```yaml
- name: Execute hello_world role from automation_bootcamp.my_collection
  hosts: all
  gather_facts: false
  tasks:
    - name: Trigger invocation of hello_world role
      ansible.builtin.include_role:
        name: automation_bootcamp.my_collection.hello_world 
```

Role Idempotency
----------------

N/A

Role Atomicity
----------------

N/A

Roll-back capabilities
----------------------

N/A

License
-------

BSD

Author Information
------------------

Matt Willis
Mike DiDato
