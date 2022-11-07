# visioplus

## Objectifs
 1. Permettre de porter les débats au coeur des foyer via une webtv
 2. Permettre aux EPCI de transformer les smartphones des élus en boitier de vote électronique
 3. intégrer ce dispositif au sein d'un process plus grand

## Réalisé
Notre version actuelle permet, en plus des fonctions de base de BBB, déjà un certain nombre de chose, comme :
- Identification eIDAS1 : 
  - LDAP (OIDc)
  - numéro GSM et confirmation par SMS
- Signature de la feuille d'émargement à l'entrée dans le salon
- Vote en direct anonyme ou public
- Pondération vote
- Procuration
- Feuille émargement à l'issue de la séance
- Résultats votes en direct et à l'issue de la séance
- Retransmission du direct sur une plateforme de streaming
- Une répartition de charge entre plusieurs serveurs
- Non gênée par les parefeux
- Séparation des flux entre le son, la voix et le partage d'écran

## Reste à réalisé
Des évolutions sont nécessaires pour faire de cet outil un outil encore plus fonctionnel pour l'univers de la territoriale qui composent nos adhérents.
Sans préjuger des évolutions de la réglementation, il est possible de faire de cet outil un outil à double usage :
- vote en présentiel et
- vote en distanciel tout en diffusant les séances sur des plateformes de streaming.
De même, une identification forte et un horodatage certifié sont certainement des pistes à explorer.

En quelques mots, voici ce qui est pressenti comme améliorations :
- Optimisation affichage pour utiliser module en boitier vote via smartphone/tablette
- Authentification forte lors de la participation à une session de vote (SMS, OTP, certificat eIDAS...)
- Préparation projet délibération en amont
- Horodatage des votes à valeur probante
- Affichage du quorum
- Limitation nombre procuration par votant
- Personnalisation documents (émargement, résultats)
- Adapter les schémas de réponse en fonction des questions
- Possibilité de voter sur une liste nominale avec choix multiple
- Interface administration des votants, plus ergonomique (peut-être 2 colonnes... Moins de scroll)
- Import en masse d'utilisateurs (invitations, votants...)
- Gestion des salons avec utilisateurs (Gestion des accès un peu comme i-delibre : utilisateurs par défaut du salon)
- Mécanismes pour les votes par collèges avec 1 votant multi casquettes
- Mise en place d'une APIRest pour communiquer avec d'autres outils (Webdelib, PASTELL...)
- Gestion multi-instance
- Installation d'une webTV (peerTube)
