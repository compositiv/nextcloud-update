nextcloud-update
=========

role for unattended installation of nextcloud updates. 

Role Variables
--------------
```yaml
nextcloud_path: path to nextcloud installation
nextcloud_fcgi_user: nextcloud fastcgi/system user
nextcloud_php_path: path to php interpreter
```

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - nextcloud-update
```

Author
------------------

Marvin Stark
