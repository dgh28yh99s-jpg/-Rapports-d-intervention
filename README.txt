T.E.I — V10.0

Nouvelle architecture :
- Accueil T.E.I
- Rapport d’intervention (module V9 conservé + pièces jointes)
- Bateau en construction
  - suivi par cale
  - pourcentage calculé selon les équipements terminés
  - ordres du jour / missions des techniciens
  - comptes rendus de fin de semaine
  - documents joints au chantier
- Notices et modes opératoires
  - recherche
  - catégories
  - pièces jointes

Données :
- IndexedDB local sur l’appareil
- Les rapports V9 existants sont conservés (même base RI_V4, version IndexedDB 2)
- Les nouvelles données sont dans les stores constructions et docs
- Sauvegarde JSON inclut rapports, bateaux, constructions et notices

iPhone :
- Icône T.E.I noire avec texte blanc
- Manifest et cache T.E.I V10
- Après publication GitHub Pages, si l’ancienne version reste affichée, fermer le site puis le rouvrir. La nouvelle icône peut nécessiter de supprimer/réajouter le raccourci à l’écran d’accueil.

Important : les pièces jointes sont stockées localement dans IndexedDB. Faire des sauvegardes régulières.
