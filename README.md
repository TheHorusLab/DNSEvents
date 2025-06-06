#### DNSEvents

 Création d'une vue personnalisée dans l'Event Viewer pour surveiller les événements liés au service DNS et son état.

 Configuration de ta vue personnalisée :

Niveaux de surveillance:
Critique
Erreur
Avertissement
Information - Pour les démarrages/arrêts

Sources:
DNS-Server-Service: Pour les opérations du serveur DNS
DNS Client Events: Pour les événements côté client

Événements critiques:
2: Démarrage du serveur DNS
4: Arrêt du serveur DNS
409: Erreur de résolution de nom
501-502: Échec de chargement de zone
6001-6002: Problèmes de réplication DNS
