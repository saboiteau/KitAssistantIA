# Guide : Mettre en place votre Veille Assistée par IA

## Pourquoi une Veille Assistée ?
Votre assistant ne doit pas seulement connaître votre passé (votre expertise), il doit aussi vous aider à comprendre le futur. Ce module vous permet de digérer 10x plus d'informations en gardant une trace structurée.

## Le Workflow en 4 étapes

### 1. Capturer (L'URL)
Dès que vous trouvez un article intéressant, ne le lisez pas tout de suite si vous n'avez pas le temps.
Copiez simplement l'URL dans une liste d'attente.

### 2. Traiter (L'Assistant)
Demandez à votre assistant de traiter l'article avec le prompt suivant :

> "Agis en tant qu'analyste expert. Voici une URL : [URL].
> Lis le contenu, et remplis le template ci-joint (Template_Fiche_Veille.md).
> Rédige tout en français, sauf le titre original et les citations directes."

### 3. Archiver (La Fiche)
Sauvegardez le résultat dans un dossier `Veille/Fiches/AAAA-MM/`.
Nommez le fichier de manière descriptive : `sujet-auteur-date.md`.

### 4. Indexer (Le Catalogue)
Tenez à jour un fichier `index.md` qui liste tous vos articles lus.
Cela permet à votre assistant de "relire" toute votre veille d'un coup pour faire des synthèses transversales (ex: "Quelles sont les tendances IA de ces 6 derniers mois basées sur ma veille ?").

## Structure recommandée des dossiers

```
Veille/
├── index.md                    # Votre catalogue
├── urls-to-process.md          # Votre liste de lecture
└── fiches/                     # Vos résumés
    └── 2025-11/
        └── article-xyz.md
```
