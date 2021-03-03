[![Build Status](https://travis-ci.com/mkoprek/ansible-role-php-fpm.svg?token=EFsRLGikq6SHNjdgZ3ra&branch=main)](https://travis-ci.com/mkoprek/ansible-role-php-fpm)

PHP-CLI / PHP-FPM Ansible Role
=========

Role for install php-cli also supports installing php-fpm on Debian/Ubuntu servers

Requirements
------------

This role requires Ansible 2.4 or higher and tested platforms are listed in the metadata file.
 
Role Variables
--------------
```yaml
php_version: 7.4
```
A PHP version you want to install, this role supports only PHP 7.0/7.1/7.2/7.3/8.0

```yaml
php_packages: []
```
A list of PHP package you want to install

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: ansible-role-php-fpm
           vars:
             php_version: 7.3

License
-------

MIT

Author Information
------------------
Role created by Maciej Koprek (mkoprek) 2021
