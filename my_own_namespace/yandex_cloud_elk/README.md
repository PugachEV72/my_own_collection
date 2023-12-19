# Ansible Collection - my_own_namespace.yandex_cloud_elk

Documentation for the collection.

=========

Данная коллеция содержит плейбук (single_task_role.yml), который использует роль (my_role),  
в которой задействован модуль (my_own_module.py) для создания текстового файла на удалённом хосте  
по заданному пути.


### Role Variables
--------------

path - задает путь и имя файла, который будет создан.  
content - задается строка, которая будет добавлена в файл.



### Example Playbook
----------------

```
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: my role }
```

### License
-------

MIT

### Author Information
------------------

Eugen Pugach
