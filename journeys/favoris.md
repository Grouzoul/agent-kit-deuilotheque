# Parcours : Gérer ses favoris

**Keywords** : favoris, sauvegarder, enregistrer, bookmarks, ressources favorites, structures favorites, mes favoris
**Auth** : requise
**Images** : logoSvg (header), soutienSvg (structures), informationSvg (ressources)

## Sections à afficher

1. Header avec logo Deuillothèque
2. Hero Banner
   - Titre : "Mes favoris"
   - Description : "Retrouvez les ressources et structures que vous avez enregistrées."
3. Section Structures favorites
   - Cartes des structures sauvegardées
   - Illustration par défaut : soutienSvg
   - Bouton : "Retirer des favoris"
4. Section Ressources favorites
   - Cartes des ressources sauvegardées
   - Illustration par défaut : informationSvg
   - Bouton : "Retirer des favoris"
5. Footer

## Routes API
- GET /items/support_structures_favorited (protégée) — Structures favorites
- GET /items/resources_favorited (protégée) — Ressources favorites
- POST /items/support_structures_favorited (protégée) — Ajouter favori structure
- POST /items/resources_favorited (protégée) — Ajouter favori ressource
- DELETE /items/support_structures_favorited/:id (protégée) — Retirer favori
- DELETE /items/resources_favorited/:id (protégée) — Retirer favori