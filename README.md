# 🌐 MeshDrive

> Un cloud souverain, sécurisé et collaboratif — construit par la communauté, pour la communauté.

---

## 🚀 Vision

Le **Drive Décentralisé** est une alternative éthique et indépendante aux solutions comme Google Drive ou Dropbox.  
Ici, **les fichiers ne sont pas hébergés sur un serveur central**, mais **répartis, chiffrés et stockés entre les utilisateurs eux-mêmes**.

Chaque participant peut :
- **Stocker** ses fichiers de manière privée et sécurisée,
- **Partager** ses ressources (espace disque, bande passante),
- **Contribuer** à la résilience du réseau tout en étant **rémunéré** pour sa participation.

## 🧩 **Structure du projet**

- **Frontend**  
  - **Technologies** : HTML / CSS / JavaScript  
  - **Dossier** : `web/`  
  - Contient l’interface utilisateur (pages web, scripts et styles).  

- **Backend**  
  - **Framework** : [FastAPI](https://fastapi.tiangolo.com/)  
  - Gère la logique métier, les requêtes et les API endpoints.  

- **Chiffrement**  
  - **Dossier principal** : `cryptolib/`  
    - Contient les **scripts Python** dédiés aux opérations de chiffrement et déchiffrement.  
  - **Dossier des clés** : `keys/`  
    - Contient des **fichiers JSON** stockant les **métadonnées** et **informations sur les fichiers uploadés**, notamment ceux **divisés en plusieurs parties** (*chunks*).  

- **Tests Peer-to-Peer (P2P)**  
  - **Dossier** : `p2p/`  
  - Contient les **scripts et outils de test** pour les échanges de fichiers entre pairs.  

- **Fichiers chiffrés**  
  - **Dossier** : `output/`  
  - Contient les **chunks chiffrés** des fichiers uploadés.
## Etat actuel
Création d'un MVP en python
