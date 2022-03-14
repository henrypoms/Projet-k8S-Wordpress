# Sujet

  • Déployez wordpress en suivant les étapes suivantes
  
  Créez un deployment mysql avec un seul replicat

  Créez un service de type clusterIP pour exposer vos pods mysql

  Créez un deployment wordpress avec les bonnes variables d’environnement pour se connecter à la base de données mysql

  Votre deployment devra stocker les données de wordpress sur un volme mounté dans le /data de votre nœud

  Créez un service de type nodeport pour exposer le frontend wordpress
