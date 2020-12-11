![GitHub Logo](/pictures/logo/Reservia%403x.png)  
**Olivier Poteau** - Soutenance du 11 décembre 2020  

Projet n° 2 du parcours "Développeur web" chez OpenClassroom.
L'objectif est d'intégrer la maquette d'un site de planification de vacance nommé "Reservia" (voir l'image ci-dessous).

## Éléments fournis:
- Maquette: [desktop](./docs/desktop.png) et [mobile](./docs/iphone8.png)
- Images: Exemple de locations, activités et logo
- Sources des icones: [Font Awesome](https://fontawesome.com/)
- Couleurs : bleu #0065FC - bleu clair #DEEBFF - gris #F2F2F2
- Police: Google Font ["Raleway"](https://fonts.google.com/specimen/Raleway)

## Cahier des charges
### Code:
- Integration en HTML5 & CSS3, sans framework
- HTML et CSS séparés dans un dossier organisé.
- Code HTML et CSS validés W3C.
- Code versionné avec git et doit avoir un repo distant sur Github ou Gitlab.
- Site compatible avec les dernières versions de Chrome et Firefox.

### UX:
- Champ de recherche est un champ de saisie éditable (fonctionnalité de recherche non implémentée pour le moment).
- Cartes d’hébergement ou d’activité cliquables dans son intégralité (liens vides pour le moment)
- Filtres non fonctionnels mais changement au survol libre.
- Menu: les liens “Hébergements” et “Activités” -> ancres qui doivent mener aux sections de la page.
- Intégration tablette à créer: adaptations libres -> breakpoints appropriés.
- Images:  taille adéquate afin qu'elle soit le plus jolie possible en impactant le moins possible le temps de chargement de la page.

## Notes sur la réalisation du projet
- La projet est hébergé sur github ici: https://github.com/oliv134/OlivierPoteau_2_09112020
- Le projet est consultable ici https://oliv134.github.io/OlivierPoteau_2_09112020/   
  GitHub Pages permet de publier un site web à partir d’un projet GitHub. Il doit être paramétré dans le dépot github concerné.  
  Afin que ce site web soit à jour lors d'un `git push`, il faur configurer un workflow.

- L'integration est faite sur l'éditeur [Visual Studio Code](https://code.visualstudio.com/).  
  Une version open source est disponible ici: [vscodium](https://vscodium.com/).
- Le code html et css est validé W3C:  
     - index.html [validator.w3.org](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&useragent=Validator.nu%2FLV+http%3A%2F%2Fvalidator.w3.org%2Fservices&acceptlanguage=&doc=https%3A%2F%2Foliv134.github.io%2FOlivierPoteau_2_09112020%2F)  
     - style.css [validator.w3.org](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Foliv134.github.io%2FOlivierPoteau_2_09112020%2Fcss%2Fstyle.css)  
     - styleSmartphone.css [validator.w3.org](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Foliv134.github.io%2FOlivierPoteau_2_09112020%2Fcss%2FstyleSmartphone.css)
     - styleTablet.css [validator.w3.org](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Foliv134.github.io%2FOlivierPoteau_2_09112020%2Fcss%2FstyleTablet.css)
- La font Google Raleway est intégrable via une déclaration dans le head du html.

- Images, logo et favicon:  
  Les Images contenues dans le dossier 4x sont de taille suffisante pour ce projet. Elles ont été renommées et contenues dans leur dossier respectif pictures/hosts, pictures/activities.  
  Le logo choisie est sa version png. Il a été croppé sous gimp pour retirer ses marges.

- Breakpoints:
     - Desktop: `(min-width: 1320px)`
     - Tablet: `(min-width: 768px) and (max-width: 1319px)`
     - Smartphone: `(max-width: 767px)`