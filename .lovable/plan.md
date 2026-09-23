# Mise à jour des offres, projets et formulaires

## Résultat attendu
- Retirer entièrement l’offre « Diagnostic Personnalisé » sans modifier les autres contenus.
- Renommer les badges des deux cartes principales en « Essentiel » et « Premium », avec le style noir demandé et les dimensions actuelles.
- Remplacer les aperçus de projets par les 10 captures jointes : 3 vues clients, 3 vues tâches, 2 vues email et 2 vues paiements.
- Retirer le titre de l’image affiché dans la barre supérieure de chaque aperçu, tout en conservant les boutons de changement de vue.
- Ajouter sous le sélecteur de projets une indication de glissement visible uniquement sur mobile lorsque la rangée déborde réellement.
- Faire aboutir les formulaires « Prendre un RDV de 20 min » et « Envoyer un message » sur l’événement Calendly fourni, avec nom, email, formule et message préremplis.

## Comportement des formulaires
- Un seul clic de validation ouvrira Calendly avec les informations déjà saisies, afin d’éviter les doubles envois.
- Le rendez-vous ne sera annoncé comme confirmé qu’après validation dans Calendly ; les créneaux fictifs locaux ne seront plus présentés comme réservés.
- Les notifications de nouveau rendez-vous seront envoyées par Calendly à l’adresse du compte organisateur, selon ses réglages de notification.

## Détails techniques
- Les images jointes seront intégrées comme ressources hébergées du projet et associées explicitement à chaque vue.
- Le débordement mobile sera détecté sur la rangée de sélection pour masquer automatiquement l’indicateur quand il n’est pas nécessaire.
- Les paramètres Calendly utiliseront le lien `https://calendly.com/rancandya/appel-decouverte-candya`, sans mois figé, avec protection contre les validations répétées.
- Les changements seront vérifiés sur mobile et ordinateur, notamment les badges, le glissement, les images et les redirections de formulaire.
