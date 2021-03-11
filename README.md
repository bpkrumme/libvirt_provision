# libvirt_provision

libvirt_provision is a collection of playbooks which can be used to define or create virtual machines on a libvirt host.

# Using the requirements.yml
A requirements.yml file is included which can be used to install the collection dependencies via ansible-galaxy or via project checkout in Ansible Tower.

### With Ansible Galaxy
If you are using the upstream Ansible project or Ansible Engine you can install the collection requirements via ansible-galaxy:

`$ ansible-galaxy install -r collections/requirements.yml`

This will install the collection to the default directory for collections on your ansible control node.

### Automatically in Ansible Tower
If you are using this repository as a project in Ansible Tower, the requirements will be downloaded and installed automatically when a job template is run.  This requires the "ENABLE COLLECTION(S) DOWNLOAD" option to be enabled in Job Settings in Ansible Tower.
