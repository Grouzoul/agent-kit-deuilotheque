# Parcours : Connexion et gestion de compte

**Keywords** : connexion, inscription, compte, login, mot de passe, profil, authentification, déconnexion
**Auth** : requise
**Images** : logoSvg (header), logoPng (page login)

## Sections à afficher

1. Header avec logo Deuillothèque
2. Section connexion
   - Titre : "Se connecter"
   - Formulaire avec email et mot de passe
   - Bouton principal : "Se connecter"
   - Lien : "Créer un compte"
   - Authentification via Keycloak (SSO)
3. Section profil (après connexion)
   - Affichage des informations utilisateur
   - Gestion des favoris (ressources et structures)
   - Bouton : "Se déconnecter"
4. Footer

## Routes API
- POST /auth/login (publique) — Connexion utilisateur
- POST /auth/refresh (protégée) — Rafraîchissement du token
- GET /users/me (protégée) — Informations du profil
- PATCH /users/me (protégée) — Mise à jour du profil