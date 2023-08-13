my_own_role
=========

Роль, созданная для тестирования Ansible Modules. Создает с помощью модуля тестовый файл по заданному пути с заданным содержимым.


Role Variables
--------------

| Var | Description | Required | Default Value |
|-----|-------------|----------|---------------|
| default_path | Path where need create file | Yes | - |
| default_content | Content will be write to the file | No | "Hello, World!" |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Create test file
        hosts: localhost
        roles:
          - my_own_role

License
-------

MIT

Author Information
------------------

Author: Kirill Shapovalov

Group: DevOps-25
