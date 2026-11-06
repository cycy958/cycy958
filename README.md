# Cyril Baussart

Ingénieur cybersécurité et IA générative, diplômé de CY Tech en 2026 après trois ans d'alternance chez Stellantis.

Je conçois des logiciels que des agents IA développent. J'écris les spécifications et les règles qu'ils suivent. Avant chaque livraison je vérifie leur travail avec des tests et dans des environnements confinés.

## Projets

### Curalis

Logiciel médical desktop en production chez un cabinet parisien depuis août 2026 (Rust, Tauri, React, SQLite).

Je l'ai fait tester par deux agents IA aux droits séparés. L'application tourne dans une VM coupée d'internet et aucun des deux ne voit le code. Pour les mettre à l'épreuve j'ai caché 18 défauts. Ils ont tous été détectés. Les agents ont ensuite trouvé 9 vrais défauts sur des versions livrées que les 1 500 tests par scripts n'avaient pas vus.

### Stellantis

Équipe CISO sur la plateforme SASE Netskope qui couvre plus de 250 000 utilisateurs.

- J'ai conçu et mis en production un service web qui publie chaque jour les adresses IP à autoriser pour une centaine de partenaires.
- Les demandes de dérogation passaient par mail. Je les ai remplacées par un circuit ServiceNow entièrement automatisé via API.
- De ma propre initiative j'ai proposé puis prototypé un agent IA qui pré-traite les tickets de l'équipe cyber. Il ne visite aucun site pour éviter l'injection de prompt et l'analyste valide chaque réponse.

### Lunero

Projet d'édition logicielle que j'ai cofondé. Curalis est son premier logiciel livré.

### Clarveo

Une fois par mois Claude et GPT débattent pour produire des plans d'allocation. Pour chaque profil le débat est lancé trois fois et un vote à majorité stricte tranche. En cas d'égalité rien n'est publié. Chaque plan est scellé par OpenTimestamps puis publié avec un mois de décalage dans [clarveo-track-record](https://github.com/cycy958/clarveo-track-record).

## Me joindre

Le plus simple est de m'écrire sur [LinkedIn](https://www.linkedin.com/in/cyril-baussart).

---

English: cybersecurity and generative AI engineer based near Paris. I design software that AI agents build, and I verify every release with tests and isolated environments.
