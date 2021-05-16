## Démo: https://ebz8.github.io/ElodieBoinZanchi_3_280421

# Ohmyfood! - Brief
### Design:
* fonts:
    - Shrikhand (logo & titres)
    - Roboto (textes)
* couleurs:
    - #9356DC (primaire - violet)
    - #FF79DA (secondaire - pink)
    - #99E2DO (tertiaire - mint)

### Technologies:
* Développement & animations exclusivement en CSS, sans JavaScript
* Utilisation de Sass
* Aucun Framework CSS

### Compatibilité:
* Mobile first : maquettes faites uniquement pour les mobiles / mise en page libre pour les tablettes et desktop
* Site responsive
* Validation au W3C
* Dernières versions de Chrome et Firefox

### Livrables:
* Page d'accueil (x1): 
    - Affichage de la localisation des restaurants, à terme choisir sa localisation pour trouver les restaurants les plus proches.
    - Courte présentation de l'entreprise.
    - Section contenant 4 menus sous forme de cartes. Au clic sur la carte, l'utilisateur est redirigé vers la page de menu.
* Page de menu (x4):
    - Chacune contenant le menu d'un restaurant.
* Footer:
    - Identique sur toutes les pages.
* Header:
    - Présent sur toutes les pages.
    - Contient le logo sur la page d'accueil.
    - Dans les pages menu, contient en plus un bouton de retour vers la page d'accueil.

### Effets graphiques et animations
(en CSS exclusivement)
* boutons :
- Couleur de fond des boutons principaux légèrement éclaircie et ombre portée plus visible au survol.
- Bouton "j'aime" qui se remplit progressivement au clic (peut apparaître au survol sur Desk).

* page d'accueil :
- Loading spinner pendant 1 à 3 secondes quand visite de la page d'accueil, qui couvre l'intégralité de l'écran. Doit être en cohérence avec la charte graphique du site. (Pas d'utilisation de librairie.)

* pages de menus :
- Plats qui apparaissent progressivement avec un léger décalage dans le temps (soit 1 par 1, soit 1 par section de menu) au chargement de la page.
- Bouton de coche qui apparait à droite du plat, qui coulisse sur la gauche, quand sélectionné par le visiteur (peut apparaitre au survol sur Desk). Si intitulé de plat trop long, rogné et apparition de "...".
