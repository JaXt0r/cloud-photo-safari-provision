require_relative '01_installation/provision/ansible_vagrant'

ansible_roles = ["default", "atom"]

vm_options = {
	memory: 4096
}
ansible_options = {
	playbook: "01_installation/provision/playbook.yml",
  tags: ansible_roles,
	extra_args: "./user.settings.yml"
}

configure_base( "AWS", ansible_roles, vm_options, ansible_options )