```
git clone https://github.com/openshift/openshift-ansible.git
cd openshift-ansible && git checkout release-3.11 
ansible-playbook -i inv ./openshift-ansible/playbooks/prerequisites.yml 
ansible-playbook -i inv ./openshift-ansible/playbooks/openshift-checks/pre-install.yml
ansible-playbook -i inv ./openshift-ansible/playbooks/deploy_cluster.yml
```
