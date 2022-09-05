# scraping-articles-lemonde-NLP

Petit projet pour le fun mélengeant du scraping via beautifulsoup et du machine learning orienté NLP

Deux idées :

- Analyser les tendances en regardant les mots les plus souvent répétés dans les titres des articles du monde sur une période
- Entrainer un algo à classer ces mêmes titres d'articles en différentes sous catégories (politique, économie, sport...)


Résultats :

- quelques trends intéressantes : par exemple le poids énorme des présidentielles dans les mots présents dans les titres

- un algo qui place les articles dans les "bonnes" catégories (donc celle prévue par le monde) à 70% 
-     -> vraiment pas mal car plusieurs catégories donc si c'était du hasard se serait moins de 10%
-     -> impactés par le volume de données, certaines catégories ayant peu d'articles performent moins
-     -> par définition métier, c'est complexe car il y'a du subjectif, un même article peut être dans plusieurs catégories et lorsque 
-     l'algo place un article catégorisé "Afrique" en "International", ce n'est pas forcément une grosse erreur

- un bon entrainement pour moi, surtout de partir de vraiment 0, et de faire la chaîne de traitement du scraping jusqu'au machine learning en un seul notebook
