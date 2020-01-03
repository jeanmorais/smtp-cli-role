smtp-cli
=========

Install [smtp-cli](http://www.logix.cz/michal/devel/smtp-cli/) — command line SMTP client.

Requirements
----------------

RedHat Enterprise (RHEL) or CentOS

Example Playbook
----------------

    - hosts: localhost
      roles:
      - role: smtp-cli
        smtp_cli_version: "3.10" # "latest" is default
