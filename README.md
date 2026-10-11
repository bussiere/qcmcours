# Entraînement QCM — Linux & Réseaux

Ce dépôt propose deux applications interactives de QCM (40 questions chacune) conçues pour tester et consolider vos compétences en conditions réelles, avec questions à choix multiples / réponses multiples, corrections pas à pas et explications détaillées.

---

## Accès direct aux QCM en ligne

Les QCM sont directement accessibles et exécutables dans n'importe quel navigateur moderne (sans installation requise) :

* 🐧 **QCM Linux utilisateur (40 questions)** :  
  👉 [https://bussiere.github.io/qcmcours/qcm_linux.html](https://bussiere.github.io/qcmcours/qcm_linux.html)

* 🌐 **QCM Réseaux informatiques (40 questions)** :  
  👉 [https://bussiere.github.io/qcmcours/qcm_reseau.html](https://bussiere.github.io/qcmcours/qcm_reseau.html)

---

## Objectifs pédagogiques

S'entraîner sur des situations réelles d'administration système et réseau :

### 🐧 QCM Linux (`qcm_linux.html`)
* **Système de fichiers & Inodes** : arborescence, chemins relatifs/absolus, métadonnées, liens physiques vs liens symboliques.
* **Droits d'accès & Masques** : calculs octaux et symboliques (`chmod`), comportement de l'`umask` sur répertoires et fichiers.
* **Édition de texte** : modes et raccourcis essentiels de l'éditeur `vi` / `vim`.
* **Processus & Signaux** : gestion d'état (`Ctrl+Z`, `bg`, `fg`), priorités (`nice`, `renice`), gestion des signaux (`SIGTERM`, `SIGKILL`, `SIGHUP`, `nohup`).
* **Flux, redirections & filtres** : descripteurs (`>`, `2>`, `2>&1`, `tee`), pipelines avec `grep`, `sort`, `uniq`, `cut`, `wc`.
* **Recherche de fichiers** : utilisation avancée de `find` (`-type`, `-size`, `-mtime`, `-exec`, `-delete`) et `locate`.
* **Environnement Bash & Scripting** : ordre d'évaluation/expansions shell, variables, persistance du `PATH` (`.bashrc`), substitutions de commandes `$()`.
* **Archivage & Planification** : manipulation de `tar` (formats gzip, bzip2, xz) et syntaxe complète du `crontab`.

### 🌐 QCM Réseaux (`qcm_reseau.html`)
* **Généralités & Topologies** : modes de transmission (simplex, half/full-duplex), types de réseaux (LAN, MAN, WAN, RIE), latence et gigue.
* **Modèles de référence** : couches OSI vs modèle TCP/IP, principes d'encapsulation et désencapsulation.
* **Couche 1 (Physique) & Câblage** : paires torsadées (catégories, longueurs maximales), fibre optique, locaux techniques (LTI/LTE).
* **Couche 2 (Liaison)** : adresses MAC, trames Ethernet, fonctionnement des commutateurs (switches, table CAM), VLANs (802.1Q) et Spanning Tree Protocol (STP).
* **Analyse de trames** : filtres d'affichage et décodage sous Wireshark.
* **Adressage IPv4 & Routage** : classes, masques, notation CIDR, tables de routage, passerelle par défaut, protocoles ARP et traceroute.
* **Couche Transport** : comparaison TCP vs UDP, établissement de connexion (3-way handshake SYN / SYN-ACK / ACK).
* **Services & Protocoles applicatifs** : NAT (SNAT, DNAT, PAT), DHCP (Discover, Offer, Request, Ack), DNS (enregistrements A, MX, PTR...), HTTP/HTTPS, messagerie (SMTP, POP, IMAP, SPF/DKIM/DMARC) et architecture sécurisée (proxys, passerelles filtrantes).

---

## 🛠️ Fonctionnalités du moteur interactif

* **Choix multiples réels** : plusieurs réponses peuvent être valides par question (système de cases à cocher).
* **Validation explicite** : vous pouvez réfléchir, cocher et décocher avant de valider votre sélection.
* **Correction instantanée et pédagogique** :
  * Verdict détaillé option par option (réponses correctement cochées, manquées ou cochées à tort).
  * Explication pas à pas et point clé à retenir 💡.
* **Bilan final** : calcul de la note sur 40, appréciation personnalisée et liste des questions à retravailler.
* **Thème clair / sombre** automatique ou commutable d'un clic.
