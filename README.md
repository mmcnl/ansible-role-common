## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: common
          vars:
            notification_email: admin@example.com
            hostname: example.com
            whitelist_ips:
              - 10.0.0.1

## License

MIT

