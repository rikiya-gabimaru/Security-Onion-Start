## Documentation Administrateur de Security Onion

### SOMMAIRE
- [Licence de cette documentation](https://github.com/rikiya-gabimaru/Security-Onion-Start?tab=readme-ov-file#licence-de-cette-documentation)
- [Prérequis techniques](https://github.com/rikiya-gabimaru/Security-Onion-Start?tab=readme-ov-file#pr%C3%A9requis-techniques-)
- [Étapes d'installation et de configuration de Security Onion 2.4](https://github.com/rikiya-gabimaru/Security-Onion-Start?tab=readme-ov-file#%C3%A9tapes-dinstallation-et-de-configuration-de-security-onion-24-)
- [FAQ](https://github.com/rikiya-gabimaru/Security-Onion-Start?tab=readme-ov-file#faq-)

### Licence de cette documentation
- Cette documentation est sous licence [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.fr)

### Prérequis techniques :

**Security Onion (Standalone) :**
  - CPU architecturex86-64 architecture (standard Intel or AMD 64-bit processors
  - CPUs : 4
  - RAM : 16 GB
  - Storage : 200 GB (testé avec 100 GB)
  - NICs : 2

### Étapes d'installation et de configuration de Security Onion 2.4 :

**1 - Téléchargement de l'ISO :**

   - [Accédez au téléchargement](https://docs.securityonion.net/en/2.4/download.html)

**2 - Vérifier l'intégrité de l'ISO :**

   - En BASH :
	```sha256sum securityonion-2.4.110-20241010.iso```
   - En CMD :
   	```certutil -hashfile securityonion-2.4.110-20241010.iso sha256```
   - En Powershell
	```Get-FileHash -Path "C:\ISO\securityonion-2.4.110-20241010.iso" -Algorithm SHA256```

**3 - Lancement de l'installation initiale :**

   - Insérer l'ISO dans la machine
   - Booter sur l'ISO
   - Sélectionner "Install Security Onion 2.4.110"
   - Configurer un nom d'administrateur et un mot de passe
   - Redémarrer la machine à la fin de l'installation initiale

**4 - Installation standard et configuration :**

- Au redémarrage de la machine, choisir "Yes" pour commencer la configuration
- Lancer l'installation standard de Security Onion
- Sélectionner *"Standard"* afin de permettre au gestionnaire d'installation d'avoir accès à Internet
- Sélectionner le type d'installation souhaité (dans notre cas STANDALONE)
- Accepter la licence en tapant *"AGREE"*
- Entrer un nom pour votre plateforme Security Onion
- Choisir l'interface réseau par laquelle la gestion admin sera effectuée
- Choisir le type d'adressage pour cette interface réseau (statique ou DHCP)
- Affecter une adresse statique pour l'interface de gestion admin (si choix de l'adressage statique)
- Entrer l'adresse de la passerelle du réseau
- Entrer l'adresse des serveurs DNS
- Entrer un nom de domaine
- Valider les informations de réseau précédemment
- Sélectionner la manière de se connecter à Internet
- Entrer une adresse web afin de permettre la connexion à l'interface web de gestion admin
- Définir un mot de passe pour la WUI puis confirmer son mot de passe
- Définir par quel moyen se connecter à la WUI (IP, HOSTNAME, OTHER)
- Autoriser l'accès via la WUI
- Définir l'IP ou les réseaux de confiances qui pourront gérer Security Onion par la WUI
- Définir l'activation ou non de la télémétrie pour aider l'équipe de développement du projet
- Valider le résumé de la configuration

**5 - Fin de configuration :**
- Valider la fenêtre de fin de configuration
  
### FAQ :
	- En cours de construction...
