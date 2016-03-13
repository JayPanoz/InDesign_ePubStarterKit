# InDesign ePub Starter Kit

L’objectif de ce kit de démarrage est de fournir des styles prédéfinis afin d’aider les utilisateurs d’InDesign à structurer sémantiquement leurs documents. Pour de plus amples informations, [consulter ce billet de blog](http://jiminy.chapalpanoz.com/wysiwyg-not-starter-kit-indesign-epub/).

Il a été conçu pour fonctionner avec toutes les versions d’InDesign capables d’exporter au format ePub.

## License

Ce kit de démarrage est placé sous licence [Creative Commons BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/fr/), ce qui signifie que vous pouvez le partager (dans les mêmes conditions et avec attribution) ou l’adapter sans toutefois en faire un usage commercial. 

Je vous encourage donc à l’étendre, le perfectionner voire réaliser des maquettes entières à partir de celui-ci.

## Installation 

1. [Téléchargez le fichier ZIP](https://github.com/JayPanoz/InDesign_ePubStarterKit/archive/v1.0.zip).
2. Dézippez le fichier téléchargé.
3. Créez une nouvelle maquette ou ouvrez un document que vous n’avez pas encore mis en pages.
4. À l’aide du menu contextuel du panneau des styles, chargez tous les styles de texte du document `ID-EPUB-starterkit.indd` (ou `ID-EPUB-starterkit.idml` si vous utilisez une version antérieure à CS6).
5. Les styles de paragraphe et de caractère du kit sont désormais disponibles dans votre document, organisés par groupes thématiques.

## Utilisation

Les styles prédéfinis n’ont pas été stylés, ils permettent simplement de structurer dans un premier temps. Seul leur balisage d’export a été travaillé et il vous faudra donc en passer par les options de style pour les modifier visuellement.

Si des styles de paragraphe et de caractère doivent être ajoutés pour les besoins de la composition, **il faudra prendre soin d'en créer un nouveau à partir d’un style prédéfini et ne surtout pas appliquer de remplacement local sur celui-ci.**

Une feuille de styles CSS pré-remplie est fournie afin de pouvoir gérer la maquette ePub à part.

Pour plus de détails, merci de consulter le guide utilisateur qui se trouve dans `assets > UserGuide`.

## Notes

- La feuille CSS a été conçue pour fonctionner de concert avec les styles qu’Indesign exporte par défaut, même si l’utilisateur spécifie qu’aucun style ne doit être généré à l’export.
- Par pragmatisme, ce kit a été conçu pour être compatible avec InDesign CS6 (ePub 2). Il devra probablement être complété pour l’export ePub 3 des versions suivantes, *a fortiori* sur les mises en pages plus complexes.
- Certaines choses étant extrêmement complexes à gérer depuis l’interface graphique d’InDesign (`pre`, `dl`, `address` et, plus généralement, tout ce qui concerne les imbrications), des compromis ont dû être faits. Les moins pires solutions ont été privilégiées – pour conserver la compatibilité avec les plus anciennes versions.
- Ce kit ne pourra pas améliorer votre export comme par magie, il a été prévu pour être **mis en place avant que le contenu ne soit traité.**
