Automating the management of applications and assets in the Corporate Asset Library (CAL) using Ansible

# Directory Structure
ansible-cal/
├── inventory
├── group_vars/
│ └── cal_servers.yml
├── manage_cal.yml
└── roles/
└── manage_cal/
├── tasks/
│ └── main.yml
└── templates/
├── add_application.json
└── add_links_template.json.j2

## Files and Directories

- **inventory**: Defines the hosts you are managing.
- **group_vars/cal_servers.yml**: Contains group variables for `cal_servers`.
- **manage_cal.yml**: Main Ansible playbook to manage CAL.
- **roles/manage_cal/tasks/main.yml**: Main tasks file for the `manage_cal` role.
- **roles/manage_cal/templates/add_application.json**: Template for adding a new application.
- **roles/manage_cal/templates/add_links_template.json.j2**: Template for adding links between applications and servers.
