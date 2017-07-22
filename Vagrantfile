require_relative '01_installation/provision/ansible_vagrant'

ansible_tags = ["atom", "nodejs"]

vm_options = {
	memory: 4096
}
ansible_options = {
	"playbook": "01_installation/provision/playbook.yml",
  tags: ansible_tags,
	extra_args: "./user.settings.yml"
}

configure_base( "AWS", vm_options, ansible_options )