# css-interrogation-privacy
 
## Consignes
Vous avez 1h40 pour intégrer le design qui se trouve dans le dossier [rendus](./rendus/). Le rendu est disponible au format Figma et Adobe XD.

Avant de commencer l'intégration :
- Veillez à bien installer les polices qui se trouvent dans le dossier [fonts](./fonts/) sur votre machine.
- Liez le fichier `reset.css` à toutes vos pages HTML.

## Rendus
### Page d'accueil (index.html)
![Rendu de la page d'accueil](./rendus/svg/Accueil.svg)
### Page article (article.html)
![Rendu de la page d'article](./rendus/svg/Article.svg)

## Documentation
Vous disposez de la documentation habituelle :
- Pocket Reference
- [MDN](https://developer.mozilla.org/fr/docs/Web/CSS) à travers les applications **Dash** ou **Zeal**
- La synthèse des étapes d'intégration via le [css-steptools](./docs/css-steptools/)

## Pondération
L'interrogation est pondérée à 12.5% de votre cote totale de l'année.
La grille d'évaluation est la suivante : 

| Lettre | Critère                                                | Description                                                                                                                                                                                                                                                                                                                                               |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **A**  | **Fichiers CSS correctement liés**                     | Vos fichiers CSS sont-ils liés en utilisant les chemins relatifs pour les différentes pages HTML ? Le fichier reset.css doit impérativement être le premier dans la liste des fichiers liés.                                                                                                                                                              |
| **B**  | **Unités relatives (% et em)**                         | Avez-vous converti toutes vos unités absolues (px) en unités relatives (em, % ou valeur numérique pour les line-height) ?                                                                                                                                                                                                                                 |
| **C**  | **Sélecteurs**                                         | Utilisez-vous les bons sélecteurs ? Préférez les sélecteurs de classe (.nom_de_la_classe) aux sélecteurs de type (nom_des_balises).                                                                                                                                                                                                                       |
| **D**  | **Padding/Margin**                                     | Faites-vous correctement la distinction entre les deux ? Le padding est la zone qui sépare le contenu de la bordure de la boîte. Le margin est l’espace autour de la boîte. Pour bien faire la différence entre les deux, il est important de savoir identifier sur quel élément se trouve l’espace.                                                      |
| **E**  | **Exercice fini dans les temps**                       | L’exercice est-il terminé dans les temps et toutes les propriétés ont-elles été modifiées ? Si vous n’avez pas réussi à terminer l’exercice, vous avez probablement besoin d’améliorer votre technique de codage en allant plus vite sur les notions typographiques élémentaires (font-size, font-family, line-height, etc.) et vos conversions d'unités. |
| **F**  | **Gestion du display**                                 | Comprenez-vous et savez-vous utiliser la propriété display lorsque c’est nécessaire ? Chaque type de boîte à un comportement bien précis qui convient à des situations spécifiques. Si vous n’arrivez pas à dissocier les deux, pensez à relire la théorie.                                                                                               |
| **G**  | **Identifier les propriétés et les valeurs à changer** | Avez-vous correctement identifié les propriétés à changer sur les bons éléments ? Le margin d'un élément n'est pas le padding de son parent, le text-decoration n'est pas une bordure, ...                                                                                                                                                                |
| **H**  | **Travail typographique**                              | Avez-vous prêté attention aux détails typographiques (couleur, décoration, graisse, taille, etc.) ?                                                                                                                                                                                                                                                       |
