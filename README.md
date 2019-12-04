## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.common
          vars:
            hostname: example.com
            monit_cpu_usage_max_pct: 80
            monit_memory_usage_max_pct: 80
            notification_email: admin@example.com
            notify_unattended_upgrades: no
            whitelist_ips:
              - 10.0.0.1
          tags: common

## License

MIT

