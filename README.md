# Ansible-Azure-NetApp-Files

Exemple de playbook qui deploie:<cd>
- un "Ressource Groupe"
- un "Virtual Network"
- un "subnet" avec le parametrage de la delegation "Microsoft.Netapp/volumes"
- un "NetApp account"
- un "Pool"  
- un "Capacity Pool"
- un Volume NSFv3


**Prérequis** :<cd/>
- Ansible avec les modules Azure (https://docs.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm?toc=https://docs.microsoft.com/fr-fr/azure/developer/ansible/toc.json)
- Collection "netapp.azure" (https://galaxy.ansible.com/netapp/azure)
- Microsoft Azure NetApp Files Management Client Library (https://pypi.org/project/azure-mgmt-netapp/)
- Azure CLi (https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
