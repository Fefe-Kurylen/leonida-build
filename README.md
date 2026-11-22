# leonida-build

Circuit de compilation iPhone de **Leonida – Carte & Missions** (éditeur Kurylen).

Ce dépôt ne contient **aucun code source** : le workflow récupère le code privé le temps de la compilation, puis envoie l'appli sur TestFlight. Rien n'est publié ici (pas d'artefacts) et les clés restent des secrets GitHub masqués.

Lancer une compilation : onglet **Actions › Leonida TestFlight › Run workflow**, ou modifier `trigger.txt`.

## Shasha

Même circuit pour **Shasha** (lecteur IPTV, éditeur Kurylen) : le code privé `Fefe-Kurylen/Shasha` est récupéré le temps de la compilation (secret `SHASHA_TOKEN`), puis l'appli part sur TestFlight.

Lancer : **Actions › Shasha TestFlight › Run workflow**, ou modifier `trigger-shasha.txt`.
