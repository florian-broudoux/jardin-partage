# Préparation de l'équipe · Le Jardin partagé des Tilleuls

## Équipe

| Membre  | Compte GitHub     | Responsabilités                          |
| ------- | ----------------- | ---------------------------------------- |
| Florian | @florian-broudoux | Developer, Scrum Master du sprint 1 et 2 |
| Laurent | —                 | Product Owner (formateur)                |

## Vision du produit

Objectif de produit : « Un habitant du quartier trouve sur son téléphone tout ce
qu'il faut pour découvrir le jardin, venir à un atelier et demander à adhérer. »

## Créneaux communs

- Mise en route (installation, 1 h) : le mardi de 9h à 10h
- Sprint 1 : planification le mardi à 10h ; revue le mardi à 12h15 ; rétrospective le mardi à 12h35
- Sprint 2 : planification le mercredi à 9h ; revue le mercredi à 11h15 ; rétrospective le mercredi à 11h35

## Accords de travail

1. Ne pas rester bloquer plus de 30min sur quelque chose, en parler des que nécessaire
2. Chacun annonce la tache qu'il va faire pour éviter les conflits
3. On répond en moins de 2h pendant les horaires prévus

## Questions pour le Product Owner

- Quels informations souhaitez vous afficher pour les ateliers du samedi matin ?
- Quels sont les horaires d'acces au jardin ?

## Product Backlog estimé

| Ordre | User story                             | Points |
| ----- | -------------------------------------- | ------ |
| 1     | US-01 En-tête et navigation communs    | 3      |
| 2     | US-09 Publication sur GitHub Pages     | 2      |
| 3     | US-08 Charte graphique (thème @theme)  | 3      |
| 4     | US-02 Page d'accueil                   | 3      |
| 5     | US-07 Pied de page et mentions légales | 3      |
| 6     | US-03 Page « Les parcelles »           | 5      |
| 7     | US-05 Formulaire d'adhésion            | 8      |
| 8     | US-04 Page « Agenda des ateliers »     | 5      |
| 9     | US-06 Page « Contact »                 | 2      |
| 10    | US-10 Page « Le compost »              | 3      |

Story de référence : US-02 Page d'accueil = 3 points · Total : … points

## Critères d'acceptation de US-10 « Le compost »

- [ ] La page est ajoutée à la navigation de toutes les pages et à vite.config.js.
- [ ] La page explique en trois étapes comment fonctionne le compost collectif.
- [ ] Deux listes qui permettent de savoir ce qu'on peut apporter dans le composteur (oui ou non)

## Définition de « terminé »

- Les critères d'acceptation sont remplis ;
- npm run build, npm run lint et npm run format:check passent sans erreur ;
- La page est lisible sur téléphone (375 px) et sur ordinateur ;
- La page s'utilise entièrement au clavier, avec un focus visible ;
- Les contrastes sont vérifiés (4,5:1 pour le texte) ;
- Le HTML est valide (validateur du W3C) ;
- La pull request est relue, approuvée et fusionnée dans main ;
- Le site en ligne est à jour.

## Sprint 1

- Objectif de sprint : « Le site est en ligne avec un en-tête et une navigation commune »
- Scrum Master : Florian
- User stories choisies (5 points) : US-01 (3), US-09 (2),
- Plan : Florian commence par US-01, puis US-09 ;
- Événements : Sprint Planning à 10h ; daily écrit avant 11h15 ; revue avec le Product Owner à 12h15 ; rétrospective à 12h35
