# Argent de Fête (prototype)

Le jeu qui calcule, **pour rire**, combien ton partenaire doit donner (ou recevoir) pour les fêtes : Noël, 31 décembre, Saint-Valentin, anniversaire.

Tu choisis un profil, tu réponds à des questions drôles, et chaque réponse ajoute ou retire de l'argent. À la fin, une carte à partager (Status WhatsApp, TikTok, Facebook...) avec le détail de chaque question.

> Ceci est un **prototype** destiné à être testé. Le paiement est simulé, rien n'est enregistré, et aucun vrai argent n'est échangé.

## Essayer le prototype

Ouvre le lien de la démo (à remplacer par ton adresse GitHub Pages) :

`https://TON-PSEUDO.github.io/argent-de-fete/`

Ou ouvre simplement le fichier `index.html` dans un navigateur.

## Ce que contient le prototype

- 9 profils, répartis en trois onglets : **Hommes**, **Femmes**, **Kpakpato**.
- Questions de mérite, de compensation et hors sujet, avec réactions de la mascotte.
- Profils multi-partenaires (menuisière, djandjou) : jusqu'à 5 partenaires, duel entre rivales et méga bonus.
- CP Braiso : juger le couple de ses amis.
- Détail de chaque question sur la carte finale, partage de chaque réponse, image de partage par partenaire.
- Tableau des comptes, première partie gratuite puis écran de paiement simulé.

## Héberger sur GitHub Pages

1. Crée un dépôt sur GitHub, par exemple `argent-de-fete`.
2. Envoie tous les fichiers de ce dossier (`Add file` puis `Upload files`).
3. Va dans **Settings** puis **Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Après une à deux minutes, le site est en ligne à l'adresse `https://TON-PSEUDO.github.io/argent-de-fete/`.

## Faire tester

Voir [TESTEURS.md](TESTEURS.md) pour le guide de test, et utilise l'onglet **Issues** de GitHub pour recueillir les retours (un modèle est prêt).

## Structure du dépôt

```
argent-de-fete/
  index.html          Le prototype complet (page unique, sans dépendance à installer)
  README.md           Ce fichier
  TESTEURS.md         Guide pour les personnes qui testent
  CHANGELOG.md        Historique des versions
  .gitignore
  .github/ISSUE_TEMPLATE/retour-testeur.md   Modèle de retour de test
```

## Limites connues

- Les parties ne sont pas sauvegardées : tout repart à zéro quand on ferme la page.
- Le paiement est simulé.
- Chaque profil a 6 questions (4 par personne en multi-partenaires), toujours dans le même ordre.
- Le partage d'image dépend du téléphone : sur certains appareils, l'image s'affiche pour être enregistrée à la main.
- La mascotte est provisoire.

## Licence

Aucune licence n'est définie : tous droits réservés. Les testeurs peuvent utiliser le prototype pour donner leur avis, mais pas le réutiliser sans accord.
