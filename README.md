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

- You will have built an inventory.. Could be inventory-as-code.

- You will have the group(s) clear on the inventory. This group is what's on your playbook hosts.

- The specific host is fed in as an extra vars and so is the command and any other things you want to achieve.
