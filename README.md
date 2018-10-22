nethserver_accounts_providers
=========

Role for manage Netserver's Account Providers.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: amygos.nethserver_accounts_providers
           vars:
             account_provider:
               type: "ldap"
               remote: false
             users_list:
               - username: "test"
                 full_name: "test"
                 password: "test"

License
-------

MIT
