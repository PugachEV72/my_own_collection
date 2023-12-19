# Домашнее задание к занятию 6 «Создание собственных модулей» - Пугач Евгений.


---

## `Подготовка к выполнению`

Создание, активация и настройка виртуального окружения my_venv

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2023-12-18_22-53-09.png)

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2023-12-18_22-56-31.png)


---

## `Основная часть`

1. В виртуальном окружении создайте новый `my_own_module.py` файл.
2. Наполните его содержимым.
3. Заполните файл в соответствии с требованиями Ansible так, чтобы он выполнял основную задачу.

### Ответ:

[my_own_module](https://github.com/PugachEV72/my_own_collection/blob/main/my_own_namespace/yandex_cloud_elk/plugins/modules/my_own_module.py)

---

4. Проверьте `module` на исполняемость локально.

### Ответ:

Для проверки был создан файл `payload.json`

[payload](https://github.com/PugachEV72/my_own_collection/blob/main/my_own_namespace/payload.json)

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2023-12-18_23-03-06.png)

---
 
5. Напишите `single task playbook` и используйте module в нём.

### Ответ:

[single_task_playbook](https://github.com/PugachEV72/my_own_collection/blob/main/my_own_namespace/single_task_playbook.yml)

---

6. Проверьте через playbook на идемпотентность. 
7. Выйдите из виртуального окружения. 

### Ответ:

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2023-12-18_23-05-16.png)

---

8. Инициализируйте новую collection.
9. В эту collection перенесите свой module в соответствующую директорию.

### Ответ:

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2023-12-19_00-23-29.png)

[modules](https://github.com/PugachEV72/my_own_collection/tree/main/my_own_namespace/yandex_cloud_elk/plugins/modules)

---

10. `Single task playbook` преобразуйте в `single task role` и перенесите в collection.
 
### Ответ:

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2023-12-19_01-26-46.png)

[my_role](https://github.com/PugachEV72/my_own_collection/tree/main/my_own_namespace/yandex_cloud_elk/roles/my_role)

---

11. Создайте playbook для использования этой role.

### Ответ:

[single_task_role](https://github.com/PugachEV72/my_own_collection/blob/main/my_own_namespace/yandex_cloud_elk/single_task_role.yml)

---

12. Заполните всю документацию по collection, выложите в свой репозиторий, поставьте тег 1.0.0 на этот коммит.

### Ответ:

[РЕПОЗИТОРИЙ](https://github.com/PugachEV72/my_own_collection/tree/main/my_own_namespace/yandex_cloud_elk)

[ТЕГ 1.0.0](https://github.com/PugachEV72/my_own_collection/tags)

---

13. Создайте `.tar.gz` этой collection в корневой директории collection. 

### Ответ:

[.tar.gz](https://github.com/PugachEV72/my_own_collection/blob/main/my_own_namespace-yandex_cloud_elk-1.0.0.tar.gz)

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2023-12-19_15-25-59.png)

---

14. Создайте ещё одну директорию любого наименования, перенесите туда single task playbook и архив c collection.
15. Установите collection из локального архива: ansible-galaxy collection install <archivename>.tar.gz.

### Ответ:

![Скриншот 8](https://github.com/PugachEV72/Images/blob/master/2023-12-19_16-01-42.png)

---

16. Запустите playbook, убедитесь, что он работает.
17. В ответ необходимо прислать ссылки на collection и tar.gz архив, а также скриншоты выполнения пунктов 4, 6, 15 и 16.

### Ответ:

![Скриншот 9](https://github.com/PugachEV72/Images/blob/master/2023-12-19_16-03-29.png)

[COLLECTION](https://github.com/PugachEV72/my_own_collection)

---
---




