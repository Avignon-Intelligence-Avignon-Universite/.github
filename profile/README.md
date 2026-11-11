# Avignon Intelligence · Avignon Université

Avignon Intelligence est le programme de déploiement de l'intelligence artificielle à Avignon Université : formation des personnels, prototypage d'outils et veille. Il est porté par la Direction d'appui à la recherche et à l'innovation (DARI), auprès du vice-président au numérique.

## Des dépôts privés, pour l'instant

Les quelque quarante dépôts de cette organisation sont privés, car ils contiennent encore des données et des configurations propres à l'université. Leur publication en open source est prévue dans le courant de l'année 2027. En attendant, voici les grandes familles d'outils développés.

### Recherche, partenariats et valorisation
Cartographie des compétences des laboratoires, construite à partir des publications en sources ouvertes (HAL, OpenAlex, ORCID, IdRef) et validée par les chercheurs. Moteur de recherche qui oriente une entreprise vers les laboratoires à partir d'un besoin exprimé en langage naturel, aide à la mise en relation, référentiel des partenaires et de leurs contrats enrichi de données publiques (SIRENE), observatoire de l'usage des outils. Une déclinaison couvre les unités INRAE du PUI Provence.

### Traduction de documents et de contenus
Traduction de fichiers Word, PowerPoint et PDF en conservant leur mise en page, traduction de conférences et de cours.

### Transcription et comptes rendus
Transcription audio avec relecture humaine, studio de transcription, génération de comptes rendus de réunions.

### Assistants pour les usagers
Assistants qui répondent à partir des pages officielles de l'université, par exemple pour l'inscription en thèse, et outils de l'expérimentation Mistral ESR.

### Pédagogie et lecture
Génération de QCM à partir de supports de cours, questions anonymes du public en cours ou en conférence avec modération et synthèse par l'IA, lecteur de PDF avec résumés et questions au document.

### Outils du quotidien
Compression de fichiers PDF et PowerPoint, correction de présentations pour OnlyOffice, prise de rendez-vous, archivage partagé, gestion d'événements comme la Fête de la science, et le portail qui rassemble ces outils.

## La démarche

- **Des sources traçables** : une information affichée renvoie à sa source.
- **La validation humaine** : l'IA propose, une personne valide, en particulier pour l'identité des chercheurs et les mots-clés.
- **Des modèles maîtrisés** : modèles exécutés en local et API Mistral de l'enseignement supérieur et de la recherche.
- **La protection des données dès la conception** : les données nominatives sont séparées des versions publiques, et la mesure d'usage est anonyme.
- **L'évaluation** : les seuils de pertinence sont calibrés par des audits, et des jeux de requêtes de référence détectent les régressions.

## La technique

Python (FastAPI, Flask), TypeScript (Express, React), SQLite, MySQL, PostgreSQL avec pgvector, ChromaDB, Docker. Les outils sont déployés sur l'infrastructure de l'université, en lien avec la direction du numérique.

## Vous êtes un établissement de l'enseignement supérieur ou de la recherche ?

Ces outils répondent à des besoins que beaucoup d'établissements partagent. Si l'un d'eux vous intéresse, ou si vous souhaitez échanger sur la démarche, contactez-moi : je peux vous présenter les outils, discuter de leur adaptation à votre contexte et vous tenir informé de leur publication en open source.

**Pierre Aumont**, coordination opérationnelle du programme · DARI, Avignon Université

[pierre.aumont@univ-avignon.fr](mailto:pierre.aumont@univ-avignon.fr) · [LinkedIn](https://www.linkedin.com/in/pierre-aumont-avignon)
