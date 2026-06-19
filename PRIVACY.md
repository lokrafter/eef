# Politique de confidentialité — EEF Apps

**Application :** EEF Apps (application Reddit/Devvit de la communauté r/EntreprendreEnFrance)
**Responsable :** l'équipe de modération de r/EntreprendreEnFrance
**Dernière mise à jour :** 19 juin 2026

## 1. Données traitées

L'application traite uniquement des **contenus publics** publiés sur le subreddit r/EntreprendreEnFrance :

- noms d'utilisateur Reddit (pseudonymes) ;
- titres, corps et scores des posts ; corps et scores des commentaires ;
- votes exprimés via l'application (l'app enregistre, par mois, le choix de vote associé à un nom d'utilisateur afin d'empêcher les votes multiples) ;
- profils « founders » et « entreprises » : résumés et catégorisations **générés automatiquement** à partir des posts/commentaires publics (voir § 5).

L'application **ne collecte pas** d'adresse e-mail, de mot de passe, de coordonnées bancaires, de données de localisation, ni aucune donnée sensible. Elle n'utilise pas de cookie publicitaire ni de traceur.

## 2. Finalités

Les données sont utilisées exclusivement pour le fonctionnement communautaire de l'app : classements d'activité, attribution de flairs (Champion, etc.), vote du mois, annuaire des AMA, et section Profils (founders/entreprises).

## 3. Base légale

Intérêt légitime de l'animation de la communauté, portant sur des contenus déjà rendus publics par leurs auteurs sur Reddit.

## 4. Stockage et conservation

Les données sont stockées sur l'infrastructure **Reddit / Devvit** (base Redis gérée par la plateforme). L'archive brute des posts est conservée de façon glissante (environ 60 jours) ; les classements et métadonnées sont conservés tant que l'app est installée.

## 5. Analyse automatisée (IA)

Les profils « founders / entreprises » sont produits par un outil d'analyse local qui soumet des **posts et commentaires publics** au modèle d'IA Claude (Anthropic) afin d'en extraire des résumés, catégories et niveaux d'expertise. Aucune donnée privée n'est transmise : seuls des contenus publics sont analysés. Le résultat est publié sous forme d'un fichier JSON public puis importé par l'application.

## 6. Requêtes externes

L'application récupère ce fichier de profils depuis un dépôt public (`raw.githubusercontent.com`). Cette requête est en **lecture seule** : aucune donnée personnelle n'est envoyée vers ce service.

## 7. Partage des données

Aucune donnée n'est vendue ni cédée. Aucun partage avec des tiers en dehors des prestataires d'infrastructure strictement nécessaires (Reddit/Devvit pour l'hébergement, Anthropic pour l'analyse de contenus publics).

## 8. Vos droits

Conformément au RGPD, vous pouvez demander l'accès, la rectification ou la suppression des données vous concernant. En pratique :

- un membre peut demander à être **retiré des classements** et de la section Profils ;
- les modérateurs disposent d'outils pour exclure un compte des classements et masquer un profil.

Pour exercer ces droits, contactez l'équipe via **le modmail de r/EntreprendreEnFrance**.

## 9. Mineurs

L'application s'adresse aux utilisateurs de Reddit conformément aux conditions d'âge de Reddit. Elle ne cible pas les mineurs.

## 10. Modifications

Cette politique peut être mise à jour ; la date de dernière mise à jour ci-dessus fait foi.

## 11. Contact

Équipe de modération de r/EntreprendreEnFrance — via modmail du subreddit.
