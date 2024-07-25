BARK: SYNC2HOST
=========

Automation to rsync files from remote server to ansible host.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**SYNC2HOST_TARGET_FILEPATH**:

The filepath on the remote server to rsync to host.

**SYNC2HOST_HOST_FILEPATH**:

The filepath on the local host to store files.

**SYNC2HOST_HOST_FILEPATH_GROUP**

The group that should own the files after copying.

**SYNC2HOST_HOST_FILEPATH_USER**

The user that should own the files after copying.

**SYNC2HOST_HOST_FILEPATH_PERMS**

The file permissions for the copied files.

Dependencies
------------

Unix/Linux operating systems.

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
