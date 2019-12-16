# B3 Devops - TP 1
## Info
mail: hugo.lantillon@ynov.com

github_username: HugoTysn21

## Etape 
Télécharger l'iso d'Ubuntu Server 18.04.3
Télécharger VirtualBox 6.0 pour eviter les pb avec vagrant
Créer une nouvelle machine virtuelle sur VirtualBox
Mettre le disque optique en première position
Choisir l'iso d'Ubuntu comme disque optique
Dans la configuration réseau, ajouter une redirection de port
Choisir 127.0.0.1 comme IP hôte 
Choisir un port hôte (2222)
Choisir un IP invité
Choisir un port invité 22
Lancer la machine virtuelle
Installer Ubuntu Server
Installer node.js :
Lancer les commandes :
  sudo apt-get update
  sudo apt-get install nodejs npm
Installer openssh (si pas installer lors de l'install d'ubuntu)
Installer nginx
Lancer iTerm et installer vagrant 
puis vagrant init (cela créer un vagrantfile)
-> vagrant up --provider=virtualbox
edit le vagrantfile pour lui indiquer le script bootstrap.sh
et pour faire le transfert de port
Lancer la commande : ssh hugo@127.0.0.1 -p 22 pour vérifier la connexion

## Etape 2