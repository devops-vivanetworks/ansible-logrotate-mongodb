# logrotate_confs/logrotate_mongodb #
Sets up hourly MongoDB log rotation. Only support for MongoDB version 3.0 or above.

## Dependencies ##
Logrotate must be installed

## Example Playbook ##

    - hosts: all
      roles:
        - role: logrotate_confs/logrotate_mongodb
          logrotate_mongodb_rotate: 1
