Настрока сервера и установка Alfresco
=========

Данная роль производит установку Alfresco Community 201605 на целевой сервер.

Требования
------------

Особые требования не предъявляются.

Переменные роли
--------------

* obraz – Расположение загружаемого образа Alfresco Community 201605 (alfresco-community-installer-201605-linux-x64.bin);
* alf_home – Директория, куда будет установлена Alfresco Community 201605;
* uninstall – Расположение деинсталлятора (используется для костыльной проверки того, что Alfresco Community 201605 уже установлена);
* admin_pass – Пароль администратора, который используется для установки Alfresco Community 201605, также является паролем ко всем БД.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - server_preparation_and_install_alfresco
