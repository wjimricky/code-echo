# Ajustements responsives de la navigation, des rendez-vous et des projets

## Résultat attendu
- Sur ordinateur, maintenir la barre de navigation sur une seule ligne avec le logo à gauche, les liens réellement centrés et « Prendre RDV » à droite.
- Dans la prise de rendez-vous, remplacer les dates figées par des dates calculées à partir du jour courant : aujourd’hui en premier, puis les jours disponibles suivants, avec mise à jour automatique au changement de date.
- Sur ordinateur, conserver l’ouverture en plein écran au survol de l’image projet.
- Sur mobile, retirer tous les accès au plein écran et ne garder que les commandes utiles au défilement des projets et des photos.
- Sur mobile, placer la commande du slider à gauche et « ← Glisser pour voir plus → » à droite, avec des espacements adaptés aux petits écrans.

## Détails techniques
- Utiliser une grille desktop à trois zones équilibrées pour garantir le centrage des liens indépendamment de la largeur du logo et du bouton.
- Générer les libellés de dates avec l’API de date du navigateur en français, sans date codée en dur, et recalculer les choix lorsque le jour civil change.
- Masquer sur mobile les boutons et liens de plein écran présents dans l’entête, la barre de vues et l’image ; rendre l’image non ouvrable au toucher.
- Regrouper sous le sélecteur mobile la flèche de navigation et l’indication de glissement sur une ligne lisible.
- Vérifier le rendu et les interactions aux formats mobile et ordinateur.
