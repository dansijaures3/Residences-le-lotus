RESIDENCES LE LOTUS — PROJET NETLIFY + GITHUB

CONTENU DU DEPOT
- index.html : site public
- admin/ : interface Decap CMS
- content/site.json : contenu modifiable
- netlify.toml : configuration Netlify et route /gestion-lotus

MISE EN LIGNE
1. Décompresser ce ZIP. Les fichiers index.html, netlify.toml et les dossiers admin/ et content/ doivent être directement à la racine du dépôt GitHub.
2. Créer un dépôt GitHub vide sur la branche main.
3. Envoyer tous les éléments décompressés à la racine du dépôt (pas le ZIP lui-même).
4. Sur Netlify : Add new project / Import an existing project > GitHub > choisir ce dépôt.
5. Pour ce site statique, laisser la commande de build vide et définir le Publish directory sur . (un point).
6. Lancer le déploiement. Netlify publiera automatiquement chaque nouveau commit envoyé sur la branche main.

ADMINISTRATION
L'interface /gestion-lotus/ est incluse, mais son authentification CMS doit être configurée séparément. La configuration actuelle utilise Git Gateway. Netlify indique désormais que Git Gateway est déprécié et déconseille les nouvelles configurations ; ne considère donc pas l'espace d'administration comme opérationnel tant que cette partie n'a pas été migrée/configurée. Le site public peut être publié indépendamment.

IMPORTANT
- Le dépôt GitHub peut être privé : autorise Netlify à y accéder pendant la connexion.
- Ne partage jamais ton mot de passe GitHub, ton token ou tes codes de connexion.
- Les tarifs actuels sont des prix d'exemple à remplacer par les tarifs validés par la résidence.
