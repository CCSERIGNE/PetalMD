
<p align="center" fontSize="60px">
  Plateforme pour lister des pokémons
</p>


## 💻 Projet

Pour développer une plate-forme Web permettant de répertorier et de visualiser les pokémons, ReactJS a été utilisé pour construire ce projet. Toutes les données sur les pokémons telles que le nom, le numéro, le type, l'image et entre autres choses étaient possibles en utilisant l'API REST [PokéApi](https://pokeapi.co/).

Ce projet est une inspiration pour une application mobile sur Pokémon, telle que [layout](https://www.behance.net/gallery/95727849/Pokdex-App)

### Fonctionnalités

- [x] **Liste des Pokémons** : Répertoriez les Pokémons à l'aide de l'API REST.

- [x] **Agrandir la liste des pokémons** : Méthode pour ajouter plus de Pokémons à la liste, augmentant le nombre de Pokémons montrés à l'utilisateur.

- [x] **Rechercher des pokémons** : Méthode pour filtrer les pokémons par leur nom.

- [x] **Effet sur la carte Pokémon** : créez une animation pour que l'utilisateur se concentre sur la carte Pokémon.

- [x] **Sélectionnez Pokémon** : Créez une page dans l'application avec plus de détails sur le Pokémon choisi.

- [x] **Créer des sections Pokémon** : séparez les informations Pokémon en trois sections : À propos, Statistiques, Évolution.

- [x] **À propos de la section** : données de base sur le Pokémon, telles que la taille, le poids, les faiblesses.

- [x] **Section des statistiques** : points de combat Pokémon, tels que la santé, l'attaque, la défense, la vitesse, l'attaque spéciale et la défense spéciale.

- [x] **Section Évolutions** : Construisez l'arbre d'évolution du Pokémon.

### Concepts abordés

- Utilisation de flexbox pour aligner et ajuster les éléments sur la page.

- Manipulation sur l'axe z à l'aide de la propriété `z-index` en css.

- Consommation d'API à l'aide de lib [axios](https://github.com/axios/axios).

- Taper des concepts à la machine à écrire.

- Utilisation du concept de fonction récursive pour créer l'arbre d'évolution Pokémon.

- Contrôle de la pagination dans la liste des pokémons et filtre par nom.

- Configuration des polices locales.

- Création d'un thème de couleur global avec `DefaultTheme` de [styled-components](https://www.styled-components.com/).

### Notes

- La liste des pokémons était limitée à 700, car à partir de ce nombre, l'api a des erreurs dans les informations du pokémon, telles que l'image, les données de combat, les caractéristiques, les données d'évolution.

- Les caractéristiques de combat de chaque Pokémon ne sont pas exactes, la raison en est que je n'ai pas trouvé la base de calcul pour chaque espèce, car il n'y a pas de schéma général et il y a plusieurs espèces j'ai décidé de limiter les informations dans ce domaine .

## :fusée: Technologies

- [Réagir](https://pt-br.reactjs.org/)
- [Styled-components](https://www.styled-components.com/)
- [React-Icons](https://react-icons.netlify.com/)
- [Axios](https://github.com/axios/axios)
- [React Router](https://reactrouter.com/web/guides/quick-start)
- [TypeScript](https://www.typescriptlang.org/)

## 📥 Installation et exécution

Clonez ce référentiel et accédez au répertoire.

```bash
$ git clone https://github.com/CCSERIGNE/PetalMD.git && cd pokedex
```

```bash
# Installation des dépendances
$ yarn

# Application en cours d'exécution
$ yarn start

```

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE.md) pour plus de détails.
