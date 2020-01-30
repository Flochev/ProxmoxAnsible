# ProxmoxAnsible
Proxmox orchestration with ansible
GROUPE 8 : 
Florian CHEVILLARD
Hérvé AKEKE



Connexion Git à Github:
	- Sur Github aller dans Settings 
	- Renseigner la clé publique (ssh) du serveur ansible
	- Sur ansible taper la commande: ssh -T git@github.com

Creation itesciadmin:
	- Creation du fichier adduser.yaml
	- Ajout de l'utilisateur itesciadmin

Configuration du pare-feu:
		On bloquaque tout le trafic entrant par défaut.
On autorise au cas par cas : 
En tapant « sudo iptables -L », une liste de vos règles actuelles est affichée.
