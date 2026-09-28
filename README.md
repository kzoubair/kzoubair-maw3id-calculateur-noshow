# kzoubair-maw3id-calculateur-noshow

Calculateur du coût des rendez-vous manqués pour cabinets médicaux et dentaires — Maw3id par Zellia

## Aperçu

`index.html` est une page web autonome (HTML, CSS et JavaScript dans un seul fichier, sans dépendance externe) qui permet à un praticien (cabinet médical ou dentaire) d'estimer :

- le nombre de rendez-vous manqués par mois ;
- la perte financière mensuelle et annuelle liée aux rendez-vous manqués ;
- le retour sur investissement de Maw3id, sur la base d'un forfait mensuel, de frais d'installation ponctuels et d'un taux de réduction des no-show estimé, avec un calcul distinct pour la 1ʳᵉ année et pour le régime établi (années suivantes) ;
- les bénéfices qualitatifs complémentaires (temps de secrétariat récupéré, liste d'attente, disponibilité 24h/24, multilingue, conformité CNDP, zéro double réservation).

La perte annuelle est affichée d'emblée ; le détail du coût et du retour sur investissement se dévoile via un bouton dédié, pour pouvoir présenter l'impact avant le prix. Tous les calculs sont mis à jour en temps réel à la saisie, directement dans le navigateur.

## Ouvrir la page en local

Aucune installation n'est nécessaire :

1. Téléchargez ou clonez ce dépôt.
2. Double-cliquez sur le fichier `index.html`, ou ouvrez-le depuis votre navigateur (`Fichier > Ouvrir...`).

La page fonctionne entièrement hors ligne, sans serveur ni connexion internet.

## Publier sur GitHub Pages

Pour rendre la page accessible via une URL publique :

1. Sur GitHub, ouvrez ce dépôt puis allez dans **Settings** (Paramètres).
2. Dans le menu de gauche, cliquez sur **Pages**.
3. Sous **Build and deployment**, choisissez la source **Deploy from a branch**.
4. Sélectionnez la branche à publier (par exemple `main`) et le dossier `/ (root)`, puis cliquez sur **Save**.
5. Après quelques minutes, GitHub affiche l'URL publique de la page (généralement de la forme `https://<utilisateur>.github.io/<nom-du-depot>/`).

Toute mise à jour poussée sur la branche configurée sera automatiquement republiée par GitHub Pages.
