# ansible
Ansible playbooks used to configure Ubuntu hosts

These are the playbooks I used to alter various configuration settings and gather specific information on Linux hosts running Ubuntu 22.04

automatic_reboot_on.yml
Congiures unattended-upgrades to reboot at 2:00 if reboot is required, even with users logged in

checkforpackage.yml
Checks if package is installed (firefox)

get_board_name.yaml
Gets system board name

get_maccaddr.yaml
Gets NIC ipv4 MAC address

reboot_if_required.yml
Reboots hosts if reboot required is detected

removesnappackage.yml
Removes snap package (firefox)

stop_and_disable_service.yaml
Stops and disables a service (bluetooth)

upgrades_off.yaml
Never notify when Ubuntu upgrade is available

wake_on_lan.yaml
Send WoL magic packet to host

unattended-upgrades.yml
Includes main updates repo but using ansible.builtin.lineinfile to uncomment line
