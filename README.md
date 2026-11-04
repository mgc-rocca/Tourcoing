# Une journée à la mairie

Jeu sérieux, pensé d'abord pour smartphone, qui présente les freins à la coopération entre services rencontrés par les agents de la ville de Tourcoing.

Réalisé par des élèves attachés de l'IRA de Lille (61e promotion) dans le cadre de la Semaine de la transformation publique (novembre 2026), à partir de dix entretiens avec des agents de la ville.

## Principe

Vous êtes agent de la ville et devez faire avancer un projet monté avec d'autres directions. La journée compte **8 situations** (de 08:12 à 17:45) et **un imprévu**. À chaque situation, vous choisissez entre trois réactions réalistes. Chaque choix agit sur trois jauges :

- **Projet** : votre projet avance-t-il ?
- **Énergie** : ce que la journée vous coûte ;
- **Règles** : restez-vous dans le cadre prévu ?

Après chaque choix, le jeu montre ce qui se passe, ce qu'ont dit les agents (citations anonymisées) et pourquoi ça bloque, avec le nombre d'entretiens, sur dix, où le problème a été évoqué.

En fin de journée, le joueur reçoit un profil (« Système D », « Dans les clous », « Équilibriste »). Le message central est qu'aucun parcours ne permet de gagner sur les trois tableaux. Le jeu présente ensuite huit pistes d'amélioration et ce qui fonctionne déjà.

Le mode **Lire sans jouer** (`#lecture`) affiche toutes les situations, tous les choix et leurs conséquences d'un seul tenant, pour une projection ou une lecture par la direction.

## Technique

- Un seul fichier `index.html` (HTML, CSS et JavaScript, sans dépendance ni étape de compilation).
- Polices Google Fonts : Bricolage Grotesque, Atkinson Hyperlegible, IBM Plex Mono.
- Thèmes clair et sombre automatiques, mouvement réduit respecté.
- Le contenu (situations, choix, citations, pistes) se trouve dans les tableaux `SCENES`, `PISTES` et `WORKS` au début du script.

## Mise en ligne

GitHub Pages : *Settings → Pages → Deploy from a branch → `main` / root*.
En local : ouvrir `index.html` dans un navigateur.

## Sources et limites

Les situations sont recomposées à partir des comptes rendus d'entretien ; les citations en sont issues, parfois resserrées, sans identification des personnes. Aucun agent des services techniques, des ressources humaines, de la direction informatique ou de la direction générale n'a été interrogé.
