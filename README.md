# example-ansible-playbook-ntpd
# Standalone ntpd integration

- Requires Ansible 1.2 or newer
- Expects CentOS/RHEL 7.x hosts

These playbook deploys a very basic configuration of ntpd as an example
from the default software repository. Edit "ntpserver" group_vars for
your ntp servers before running the playbook.

Then run the playbook:

        ansible-playbook ntpd.yml

After runnung the playbook you'll have an installed and configured ntpd.
