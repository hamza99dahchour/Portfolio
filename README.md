# Portfolio — Hamza Dahchour

Site personnel one-page, disponible en français et en anglais, construit sur le modèle du portfolio de Mourad Harzallah (mêmes sections : À propos, Expérience, Projets, Compétences, Activités, Articles, Témoignage, Contact), avec une charte graphique crème / vert foncé / orange.

## Fichiers

- `index.html` — page principale (français)
- `index-en.html` — page principale (anglais)
- `article1.html` / `article1-en.html` — mémoire Carrefour (FR / EN)
- `article2.html` / `article2-en.html` — l'effet barbecue (FR / EN)
- `article3.html` / `article3-en.html` — parcours (FR / EN)
- `hero-photo-real.png` — photo de couverture
- `logo-ucsd.jpg`, `logo-ibm.png`, `logo-google-data-analytics.jpg` — logos des certifications
- `HD-logo-avatar-500.png` — logo/avatar GitHub
- `CV_Hamza_Dahchour_Data_Scientist.pdf` — CV téléchargeable

## Nouveautés de cette version

- **Sélecteur de langue FR/EN** en haut à droite de la navigation (sur toutes les pages)
- **Expérience professionnelle condensée** : chaque poste affiche 2 points clés par défaut, avec un bouton "Voir plus" pour dérouler le détail complet
- **Email protégé du scraping** : l'adresse n'apparaît plus en clair dans le code source HTML (elle est recomposée par JavaScript au chargement de la page et à l'ouverture du client mail)
- **Champ Email obligatoire** dans le formulaire de contact, marqué d'un astérisque rouge
- **Localisation reformulée** : "Actuellement en Île-de-France · mobilité France entière" à la place de "Mobile en France"
- **Badge "Enchanté" supprimé** du hero
- **Citation attribuée** à Hamza Dahchour dans la section À propos

## À personnaliser avant mise en ligne

1. **LinkedIn** : vérifiez que `https://linkedin.com/in/hamza-dahchour` est bien votre URL réelle.
2. **Formulaire de contact** : pointe déjà vers votre Formspree (`mqerkerz`) — vérifiez qu'il reste actif.
3. **Liens GitHub des projets** : les cartes "Détection de fraude" et "Système décisionnel achats & commandes" pointent vers `#`. Remplacez par vos dépôts réels.
4. **Articles en anglais** : relisez les traductions et ajustez si besoin (ex. niveau d'anglais mentionné dans l'article 3, à harmoniser avec la section Compétences si vous la modifiez à nouveau).

## Mise en ligne sur GitHub Pages

1. Créez un dépôt nommé exactement `VOTRE-PSEUDO-GITHUB.github.io`.
2. Ajoutez tous les fichiers de ce dossier à la racine du dépôt (upload web, ou `git add . && git commit -m "Mise à jour" && git push`).
3. Dans **Settings → Pages**, vérifiez que la source est la branche `main` / dossier racine.
4. Le site est disponible à `https://VOTRE-PSEUDO-GITHUB.github.io`.
