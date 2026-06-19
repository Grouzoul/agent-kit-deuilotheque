# Parcours : Rechercher une structure de soutien

**Keywords** : annuaire, structure, soutien, accompagnement, association, recherche, proximité, localisation, carte
**Auth** : non requise
**Images** : logoSvg (header), homepageModulesAnnuaireSvg (hero), soutienSvg (cards)

## Sections à afficher

1. Header avec logo Deuillothèque
2. Hero Banner
   - Titre : "Annuaire des structures de soutien"
   - Description : "Trouvez une structure d'accompagnement au deuil près de chez vous."
   - Illustration : homepageModulesAnnuaireSvg
3. Barre de recherche
   - Placeholder : "Rechercher une structure..."
   - Recherche par localisation (calcul de distance via haversine)
4. Liste de résultats sous forme de cartes
   - Chaque carte affiche : nom de la structure, type de service, localisation
   - Illustration par défaut : soutienSvg
5. Footer

## Routes API
- GET /items/support_structures (publique) — Liste des structures de soutien
- GET /items/services (publique) — Liste des types de services proposés