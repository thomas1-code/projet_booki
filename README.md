# Spécifications fonctionnelles

● Les usagers pourront rechercher des hébergements dans la ville de
leur choix. Le champ de recherche est un champ de saisie, le texte
doit donc pouvoir être édité par l’utilisateur. Il faut englober ce
champ dans un formulaire pour que ce dernier soit valide auprès du
W3C. La partie recherche ne doit pas être fonctionnelle.

● Chaque carte d’hébergement ou d’activité devra être cliquable dans
son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
vides. On peut utiliser un attribut `href=”#”` pour simuler la
présence d’un lien.

● Les filtres doivent changer d’apparence au survol. Ils ne doivent pas être fonctionnels.

● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont
des liens. Ils doivent mener respectivement vers la section
“Hébergements à Marseille” et “Activités à Marseille”.

# Spécifications techniques

● Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le
site devra être également adapté aux formats tablette. Pour les
tablettes, nous sommes libres de faire les adaptations nécessaires. Il
est important qu’aucun élément ne soit coupé, et que le texte ait
une taille suffisante.

● Concernant les breakpoints, nous avons convenu avec le designer UI
d’utiliser 992 px et 768 px.

● Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement
dit, en desktop first), puis les tablettes et enfin les téléphones.

● Il est important d’utiliser les pixels et les pourcentages plutôt que les
REM et les EM.

● Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno
que l’équipe maîtrise le mieux.

● Aucun framework CSS (type BootStrap ou Tailwind CSS) ou
préprocesseur CSS (type Sass ou Less) ne doit être utilisé.

● Il est important d’utiliser des balises sémantiques (type `main`,
`header`, `nav`, etc.).

● Le code doit être valide aux validateurs W3C HTML et CSS.

● La maquette doit être compatible avec les dernières versions de
Google Chrome et de Mozilla Firefox.