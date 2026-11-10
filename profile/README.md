# Avignon Intelligence · Avignon Université

Avignon Intelligence est le programme de déploiement de l'intelligence artificielle à Avignon Université : formation des personnels, prototypage d'outils et veille. Il est porté par la Direction d'appui à la recherche et à l'innovation (DARI), auprès du vice-président au numérique.

Les dépôts de cette organisation sont privés pour le moment, car ils contiennent des données et des configurations internes à l'université. Cette page présente les outils et la démarche du programme.

## Les outils

### Cartographie des compétences des laboratoires
Un moteur de recherche oriente une entreprise vers les laboratoires de l'université à partir d'un besoin exprimé en langage naturel. Il s'appuie sur les publications des chercheurs dans des sources ouvertes (HAL, OpenAlex, ORCID, IdRef). Chaque chercheur est identifié par ses identifiants pérennes, et les profils sont validés par les chercheurs eux-mêmes. Une déclinaison couvre les unités INRAE du PUI Provence.

### Observatoire de la valorisation
Un tableau de bord suit l'usage, anonymisé, des outils publics : indicateurs, évolution dans le temps, parcours des utilisateurs.

### Référentiel des partenaires
Une base des partenaires de l'université est enrichie de données publiques (SIRENE, API Recherche d'entreprises). Ces données externes restent toujours distinguées des données internes.

### Outils internes
Le programme développe aussi des assistants qui répondent à partir des pages officielles de l'université, un outil de traduction de documents qui conserve leur mise en page, et des outils de transcription et de compte rendu de réunions.

## La démarche

- **Des sources traçables** : une information affichée renvoie à sa source.
- **La validation humaine** : l'IA propose, une personne valide, en particulier pour l'identité des chercheurs et les mots-clés.
- **Des modèles maîtrisés** : modèles exécutés en local et API Mistral de l'enseignement supérieur et de la recherche.
- **La protection des données dès la conception** : les données nominatives sont séparées des versions publiques, et la mesure d'usage est anonyme.
- **L'évaluation** : les seuils de pertinence sont calibrés par des audits, et des jeux de requêtes de référence détectent les régressions.

## La technique

Python (FastAPI, Flask), TypeScript (Express, React), SQLite, MySQL, PostgreSQL avec pgvector, ChromaDB, Docker. Les outils sont déployés sur l'infrastructure de l'université, en lien avec la direction du numérique.

## Contact

Pierre Aumont, coordination opérationnelle du programme et administration de cette organisation · DARI, Avignon Université
