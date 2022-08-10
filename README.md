Logstash
=========

Simple download binaries from official website and install logstash.

Role Variables
--------------
There is only two variables that you can redefine in your playbook.
```yaml
elastic_version: "8.3.3" # Use for download only this version of elastic
elastic_home: "/opt/logstash/{{ logstash_version }}" # Use for unpackage distro and create ES_HOME variable
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: all
  roles:
      - logstash
```

License
-------

BSD

Author Information
------------------

Konstantin Mankov
