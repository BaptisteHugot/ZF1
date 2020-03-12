# ZF1
Ce programme affiche une carte montrant les communes faisant partie de la ZF1 (celles dont la densité d'établissements de plus de dix salariés dans la commune est supérieure à 20 établissements par kilomètres carrés, dont le nombre d'accès BLOD construits sur la commune est supérieur ou égal à 50 accès et dont au moins la moitié de ces accès sont construits sur des infrastructures n'appartenant pas à Orange).
<a/>
Les données sont tirées du fichier disponible sur le site de l'[Arcep](https://www.arcep.fr/la-regulation/grands-dossiers-reseaux-fixes/la-regulation-du-marche-telecom-entreprises/la-regulation-tarifaire-des-offres-entreprises-sur-la-fibre-dediee.html), le régulateur des communications électroniques en France.

## Exemple
Un exemple complet est disponible sur [ma page personnelle GitHub](https://baptistehugot.github.io/ZF1/), et un exemple de rendu de cette carte au format .png est disponible ci-dessous.

<img src="https://user-images.githubusercontent.com/19981614/76576216-bf597c80-64c1-11ea-859d-30a597197e11.png" width="30%"></img>

## Ecrit avec
* [Javascript](https://www.ecma-international.org/publications/standards/Ecma-262.htm) - Le langage de programmation utilisé pour gérer la gestion de la carte et des bibliothèques
* [HTML](https://www.w3.org/html/) - Le langage de programmation utilisé pour afficher la page Internet
* [CSS](https://www.w3.org/Style/CSS/) - Le langage de programmation utilisé pour gérer les styles de la page Internet

## Bibliothèques utilisées
* [Leaflet](https://leafletjs.com/) - La bibliothèque utilisée pour afficher la carte
* [Leaflet-Ajax](https://github.com/calvinmetcalf/leaflet-ajax) - La bibliothèque utilisée pour gérer l'affichage des zones contenues dans le fichier GeoJson
* [Leaflet-Geosearch](https://github.com/smeijer/leaflet-geosearch) - La bibliothèque utilisée pour permettre la recherche par commune
* [Leaflet-Locatecontrol](https://github.com/domoritz/leaflet-locatecontrol) - La bibliothèque utilisée pour permettre la géolocalisation de l'utilisateur
* [Leaflet.fullscreen](https://github.com/Leaflet/Leaflet.fullscreen) - La bibliothèque utilisée pour afficher la carte en plein écran
* [Leaflet-Hash](https://github.com/mlevans/leaflet-hash) - La bibliothèque utilisée pour avoir une URL dynamique au lieu d'une URL statique par défaut
* [Leaflet-easyPrint](https://github.com/rowanwins/leaflet-easyPrint/) - La bibliothèque utilisée pour exporter la carte au format .png et pour l'imprimer

## Versions
[SemVer](http://semver.org/) est utilisé pour la gestion de versions. Pour connaître les versions disponibles, veuillez vous référer aux [étiquettes disponibles dans ce dépôt](https://github.com/BaptisteHugot/ZF1/releases/).

## Auteurs
* **Baptiste Hugot** - *Travail initial* - [BaptisteHugot](https://github.com/BaptisteHugot)

## Licence
Ce projet est disponible sous licence logiciel MIT. Veuillez lire le fichier [LICENSE](LICENSE) pour plus de détails.

## Règles de conduite
Pour connaître l'ensemble des règles de conduite à respecter sur ce dépôt, veuillez lire le fichier [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Contribution au projet
Si vous souhaitez contribuer au projet, que ce soit en corrigeant des bogues ou en proposant de nouvelles fonctionnalités, veuillez lire le fichier [CONTRIBUTING.md](CONTRIBUTING.md) pour plus de détails.