# Livrable 1: Analyse de l'environnement informatique d'une entreprise à partir d'une offre d'emploi ISR

<!--

Remplissez ce document au format Markdown. Utilisez Visual Studio Code avec le mode Preview activé.


-->
- **Quoi remettre**: Ce document en format *Markdown* nommé `livrable1-analyse.md`.
- **Où faire la remise**: sur GitLab (cet après-midi)
- **Correction du fichier par le professeur**: le 20 janvier à 11h



Choisissez une offre d'emploi en lien avec l'ISR et analysez cette entreprise pour imaginer son environnement informatique.


## 1. Informations générales

- **Nom de l’entreprise** :HNA S.E.N.C.R.L
- **Secteur d’activité** :Services comptables et conseils en fiscalité.  
- **Taille de l’entreprise** :  
  - Nombre d’employés :  Environ 200  
  - Nombre de bureaux/sites : 2 au Canada  
- **Activités principales** :Cabinet comptable multidisciplinaire offrant des services-conseils, certification, fiscalité, comptabilité et solutions infonuagiques.


## 2. Besoins en infrastructure TI

**Réseaux**

- Type d’infrastructure réseau : LAN avec VLANs pour les sites physiques et Wi-Fi sécurisé  
- Technologies envisagées : Commutateurs gérés, pare-feu, VPN pour télétravail  

**Virtualisation et serveurs**

- Type d’hyperviseur : VMware 
- Nombre de serveurs physiques et virtuels : Probablement 2 a 3 serveurs physiques avec 10-15 VMs pour la gestion des solutions Microsoft 365, Active Directory, Exchange et SharePoint
- Services prévus : Active Directory, DNS, DHCP, Exchange Online, SharePoint Online, SQL Server 
- Stockage: One Drive

**Cloud**

- Modèle de cloud : Hybride
- Utilisation prévue :  
  - Stockage objet : Sauvegardes, documents partagés sur OneDrive et SharePoint
  - Applications web : Hébergement d’applications internes via IIS ou plateformes cloud  
  - Environnement de développement/test.  : Projets d’innovation technologique.

## 3. Besoins en sécurité

**Protection des données**

- Sauvegardes : Sauvegardes régulières avec solutions Microsoft 365 intégrées et chiffrement des données.
- Politique de rétention :Minimum 30 jours pour les journaux critiques et sauvegardes à long terme pour les projets comptables. 

**Accès sécurisé**

- VPN : VPN pour télétravail hybride et site-à-site.
- Authentification : Authentification multi-facteurs (MFA) via Microsoft Entra ID (Azure AD).
**Supervision et réponse aux incidents**
- Outils de supervision : Zabbix ou Elastic Stack pour la surveillance des serveurs, réseaux et applications critiques.
- Plan de continuité : Tests réguliers de récupération, documentés dans les procédures internes.


## 4. Présentation structurée

- **Format Markdown** : Le document doit être clair et bien structuré, avec titres, sous-titres et listes.
<!-- - **Dépôt Git** : Héberger le document sur GitHub ou GitLab pour un suivi collaboratif. -->

---


# Grille de correction


| **Critère**                         | **Poids** | **Description**                                                                                                                                                    | **Évaluation (points)**         |
|-------------------------------------|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|
| **1. Informations générales**       | 10 %      | L’entreprise est clairement identifiée et décrite (secteur, taille, activité principale). Les informations sont cohérentes et pertinentes pour le projet.          | **0-2** : Incomplet ou incohérent. <br>**3-4** : Acceptable mais des éléments manquent ou sont flous. <br>**5** : Complet, clair et réaliste. |
| **2. Besoins en infrastructure TI** | 30 %      | Les besoins réseau, serveurs, virtualisation et cloud sont bien définis et adaptés à l’entreprise. Les choix sont justifiés et réalistes.                          | **0-6** : Trop générique ou irréaliste. <br>**7-13** : Justifications partielles ou simplistes. <br>**14-15** : Analyse complète et bien structurée. |
| **3. Besoins en sécurité**          | 20 %      | Les mesures de protection des données, d’accès sécurisé et de supervision sont pertinentes et adaptées. Une logique claire sous-tend les choix proposés.          | **0-4** : Superficiel ou manquant. <br>**5-7** : Pertinent mais peu détaillé. <br>**8-10** : Excellent, bien justifié et précis. |
| **4. Présentation et format**       | 15 %      | Document bien structuré en Markdown, respectant le modèle fourni. Les informations sont claires et faciles à lire (titres, sous-titres, liens, etc.).             | **0-2** : Désordonné ou non conforme. <br>**3-4** : Lisible mais quelques manques. <br>**5** : Parfaitement structuré et respectueux du format. |
| **Participation active (critère individuel)**         | --      | L'étudiant a activement participé aux discussions en classe, en contribuant avec des idées ou des arguments constructifs.                                            | **Aucune pénalité** : Participation active et constructive. <br> **50% de pénalité sur le livrable** : Participation minimale ou non constructive. <br> **100% de pénalité sur le livrable** : Aucune participation. |

---
