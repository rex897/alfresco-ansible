Установка Бизнес-платформы
=========

Данная роль производит установку пакета Бизнес-логика для Alfresco Community 201605.

Требования
------------

Особые требования не предъявляются.

Переменные роли
--------------

* alf_home: – Директория, куда будет установлена Alfresco Community 201605;
* alf_data_home: "{{ alf_home }}/alf_data";
* catalina_home: Директория, где расположены файлы Tomcat;
* admin_pass: – Пароль администратора, который используется для установки Alfresco Community 201605, также является паролем ко всем БД.

Example Playbook
----------------

    - hosts: servers
      roles:
         - installing_a_business_platform