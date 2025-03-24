## **Tâche 1 : Métiers Principaux et Composantes IT Critiques par Niveau**

---

#### **A. RDC (Rez-de-Chaussée)**  
Le RDC est dédié à l’accueil, aux consultations générales et aux tâches administratives.

##### **Métiers Principaux** :
1. **Agent d’Accueil (Réceptionniste)** :
   - Gère l’accueil des patients, les inscriptions et les rendez-vous.
2. **Secrétaires Médicales** :
   - Gèrent les dossiers des patients, les rendez-vous et les tâches administratives.
3. **Médecins Généralistes** :
   - Consultent les patients pour des diagnostics généraux.
4. **Infirmiers/Infirmières** :
   - Assistants les médecins et prodiguent des soins de base.

##### **Composantes IT Critiques** :
1. **Bureautique** :
   - **Email** : Pour la communication interne et externe.
   - **Logiciels de Productivité** : Traitement de texte, tableurs et présentations.
2. **Réseau** :
   - **LAN** : Connecte les ordinateurs de l’accueil et des secrétaires.
   - **Wi-Fi** : Accès internet pour le personnel et les patients.
3. **Logiciel de Prise de Rendez-vous** :
   - Gère les rendez-vous des patients et envoie des rappels.
4. **Système de Facturation** :
   - Gère la facturation des patients et les demandes de remboursement.
5. **Portail Patient** :
   - Permet aux patients de prendre des rendez-vous en ligne et d’accéder à leurs informations.

---

#### **B. 1er Étage**  
Le 1er étage est dédié aux consultations spécialisées (cardiologie) et aux soins.

##### **Métiers Principaux** :
1. **Cardiologues** :
   - Consultent les patients pour des problèmes cardiaques spécifiques.
2. **Infirmiers/Infirmières Spécialisés** :
   - Assistants les cardiologues et gèrent les soins spécialisés.
3. **Techniciens de Bloc Médical** :
   - Opèrent et entretiennent les équipements médicaux (par exemple, ECG, moniteurs cardiaques).

##### **Composantes IT Critiques** :
1. **Dossier Médical Électronique (DME)** :
   - Stocke les dossiers des patients, y compris les diagnostics et les traitements.
   - Accessible aux médecins et infirmiers pour une consultation rapide.
2. **Système de Gestion du Bloc Médical** :
   - Suit l’utilisation et la maintenance des équipements médicaux.
3. **Sécurité** :
   - **Firewall** : Protège les données médicales sensibles.
   - **Antivirus** : Protège les ordinateurs contre les logiciels malveillants.
4. **Communication** :
   - **VoIP** : Pour les appels internes entre les médecins et les infirmiers.

---

#### **C. 2e Étage**  
Le 2e étage est dédié au laboratoire et aux analyses médicales.

##### **Métiers Principaux** :
1. **Techniciens de Laboratoire** :
   - Réalisent des analyses médicales (par exemple, analyses sanguines, ECG).
2. **Biologistes Médicaux** :
   - Interprètent les résultats des analyses et fournissent des rapports aux médecins.
3. **Responsable du Laboratoire** :
   - Supervise les activités du laboratoire et assure la qualité des analyses.

##### **Composantes IT Critiques** :
1. **Système de Gestion de Laboratoire (LIS)** :
   - Gère les analyses de laboratoire, enregistre les résultats et les intègre au DME.
2. **Stockage Cloud** :
   - Sauvegarde les résultats d’analyses et les rapports médicaux.
3. **Sécurité** :
   - **Sauvegarde des Données** : Pour éviter la perte des résultats d’analyses.
4. **Communication** :
   - **Imprimante/Scanner** : Pour imprimer les rapports d’analyses et numériser les documents.

---



## **Tâche 2 : Tableau de Bord de la Sécurité des Systèmes d'Information**

**_Voyez les fichiers Excel joints, qui sont répartis entre les TDB de la sécurité réseau - Bureautique - DB , la sécurité physique et la Sécurité des Employés._**

## **Tâche 3 : Lois Existantes et Évolutions Futures pour les Données**

En tant que RSSI de cet hôpital, j'ai réalisé une analyse pour détecter les points valides et non valides, afin de respecter la lois. J'ai répondu à une série de questions concernant les aspects existants et non existants liés à la sécurité réseau, bureautique, des bases de données, ainsi qu'à la sécurité physique et des employés. Vous pouvez consulter les tableaux de bord dans la tâche 2. Dans cette tâche, je vais me concentrer sur les points qui, en leur absence, peuvent affecter les données des clients, ainsi que sur les mesures que nous prévoyons d'ajouter à l'avenir pour améliorer le pourcentage de sécurité.

### **Loi 09-08**

En tant que RSSI de cet hôpital situé au Maroc, il est crucial de respecter les lois régissant la cybersécurité, notamment la loi 09-08 relative à la protection des données personnelles. Afin de garantir la conformité avec cette législation, nous avons mis en place des mesures de sécurité rigoureuses sur l'ensemble de notre réseau local. Ces mesures assurent le respect des principes fondamentaux de la CIA (Confidentialité, Intégrité, Disponibilité) :

- **Confidentialité** : Nous avons renforcé la protection des applications à travers des mécanismes d'authentification robustes et l'intégration de l'authentification à deux facteurs (2FA) afin de sécuriser l'accès aux informations sensibles.
- **Intégrité** : Les données des patients sont stockées sur des serveurs hautement sécurisés et chiffrés, garantissant leur préservation contre toute altération non autorisée.
- **Disponibilité** : En raison de l'importance de l'accessibilité continue aux applications, nous avons assuré leur bon fonctionnement sur le réseau local, même en l'absence d'Internet. De plus, pour pallier toute défaillance d'alimentation, un système de batteries de secours, alimentées par l'énergie solaire, a été mis en place.

Par ailleurs, toutes les communications internes au sein de l'hôpital sont sécurisées et chiffrées, garantissant la confidentialité des échanges et la sécurité des informations échangées.

### Mesures à Ajouter pour Renforcer la Conformité à la Loi 09-08

Bien que de nombreuses mesures aient déjà été mises en place, il existe plusieurs actions futures à ajouter pour améliorer encore notre conformité avec la loi 09-08 :

1. **Implémentation de la Technologie RAID 1+0**  
    Nous prévoyons d'ajouter la technologie RAID 1+0 pour garantir une redondance accrue des données et leur disponibilité continue. En cas de défaillance matérielle, cette configuration assurera la continuité de l'accès aux données critiques des patients.
    
2. **Amélioration des Systèmes de Sauvegarde**  
    Des sauvegardes supplémentaires seront effectuées sur des systèmes externes et des supports sécurisés, garantissant une récupération rapide des données en cas d'incident majeur.
    
3. **Renforcement des Mécanismes de Surveillance et d'Audit**  
    Un système de surveillance et d'audit plus sophistiqué sera intégré pour détecter toute tentative d'accès non autorisé ou d'anomalie dans les systèmes, permettant ainsi une réaction rapide en cas de menace.
    

Ces actions futures permettront non seulement de renforcer la sécurité des données sensibles, mais également d'améliorer l'efficacité opérationnelle et la résilience des systèmes face aux risques.


### **Loi 43-20** 

La loi n° 43-20 régit la protection des données personnelles dans le cadre des paiements électroniques au Maroc. Elle impose des normes strictes pour garantir la sécurité et la confidentialité des informations sensibles échangées lors des transactions, notamment celles liées aux paiements par carte bancaire.
### Situation Actuelle et Futurs Plans

Actuellement, l'hôpital utilise des paiements par carte bancaire via une plateforme tierce, PayPal, pour traiter les transactions des patients. Cependant, cette solution ne respecte pas pleinement les exigences de la loi n° 43-20, ce qui présente des risques potentiels pour la sécurité des données. Dans nos futurs projets, nous prévoyons de passer à une solution 100% marocaine, le **CMI (Centre Monétique Interbancaire)**, pour assurer la conformité avec la législation en vigueur et garantir une sécurité optimale des transactions financières.

### **Loi 05-20**

La loi n° 05-20 régit la cybersécurité au Maroc en imposant des normes pour assurer la protection des systèmes d'information et des données numériques contre les cybermenaces. En tant que RSSI de cet hôpital, ma mission consiste à garantir la sécurité de tous nos systèmes d'information, en veillant à leur conformité avec cette législation.

### Mesures Actuelles et Futures

Actuellement, nous avons mis en place des mesures de sécurité rigoureuses pour protéger nos systèmes et données, et dans le cadre de nos projets futurs, nous prévoyons de constituer une équipe dédiée à la cybersécurité. Cette équipe comprendra :

1. **Un Pentester** pour tester la sécurité de tous nos systèmes développés et des nouvelles machines de l'hôpital.
2. **Un Analyste SOC** pour surveiller et détecter tout trafic non autorisé afin d'agir rapidement en cas de tentative d'intrusion.

Ces actions permettront de renforcer encore la protection des données et d'améliorer la résilience de notre infrastructure face aux menaces futures.
