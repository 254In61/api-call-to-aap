# api-call-to-aap
- A repo to simulate api calls to ansible automation platform to kick-start jobs

# Tit bits
- Please make sure the "Prompt on launch" is enabled under the "Extra variables" in the job template.

- To enable use the following steps:

  1. Edit the job template in Ansible Tower webUI
  
  2. In the details tab, scroll down to "Extra variables"

  3. Select the "Prompt on launch"
  
  4. Save the template

# How-to

- You would have built the organization, credential and project AAP objects.

- You would have built an inventory.. Could be inventory-as-code.

- You would have built your job-template AAP object..It will have the right machine credential attached and the right inventory.

- Your playbook 'hosts' will be reffering to a group that is contained in the inventory above and also the group has the target hosts underneath it.

- The specific host is fed in as an extra vars and so is the command and any other things you want to achieve.
