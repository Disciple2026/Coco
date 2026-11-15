# Coco.P Infusion

Site vitrine de Coco.P Infusion : bissap nature, bissap menthe et gnamakou (gingembre, ananas), livrés gratuitement à Tanger. Les commandes passent par WhatsApp.

## Contenu

- `index.html` : la page, en un seul fichier (HTML, CSS, JavaScript).
- `assets/` : les modèles 3D (`.glb`) et les images des cartes.

## Voir le site en local

Les modèles 3D ne se chargent pas en ouvrant `index.html` par double-clic. Il faut un petit serveur :

```
python -m http.server 8765
```

puis ouvrir http://127.0.0.1:8765

## Mise en ligne

Site statique, sans étape de build : sur Netlify, laisser la commande de build vide et publier la racine du dépôt.
