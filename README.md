# Ansible-Azure-NetApp-Files

Exemple de playbook qui deploie:<cd>
- un "Ressource Groupe"
- un "Virtual Network"
- un "subnet" avec le parametrage de la delegation "Microsoft.Netapp/volumes"
- un Compte NetApp
- un "Pool"  
- un "Capacity Pool"
- un Volume NSFv3


**Prérequis** :<cd/>
- Ubuntu 18.04 TLS
- Ansible avec les modules Azure
- Collection "netapp.azure"
- Microsoft Azure NetApp Files Management Client Library
- En Option Azure CLi (delagation du subnet "Microsoft.Netapp/volumes")

