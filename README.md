Filebeat role
=========

Роль для установки filebeat на хостах с ОС: CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| elk_stack_version | "7.14.0" | Параметр, который определяет какой версии filebeat будет установлен |


Example Playbook
----------------

```bash
  - hosts: filebeat
    become: true
    roles:
      - { role: filebeat-role, tags: filebeat }
```
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
