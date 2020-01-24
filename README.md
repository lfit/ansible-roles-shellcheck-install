shellcheck-install
==================

Install ShellCheck.

Requirements
------------

None.

Role Variables
--------------

shellcheck_checksum: checksum of shellcheck archive.
shellcheck_version: version of shellcheck to install.


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lfit.shellcheck-install }

License
-------

MIT

Author Information
------------------

Linux Foundation Release Engineering
