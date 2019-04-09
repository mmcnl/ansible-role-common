## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: common
          vars:
            hostname: example.com
            whitelist_ips:
              - 10.0.0.1

## License

MIT

