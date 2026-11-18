# Politique de confidentialité · EEF Apps

**Application :** EEF Apps (application Reddit/Devvit de la communauté r/EntreprendreEnFrance)
**Responsable :** l'équipe de modération de r/EntreprendreEnFrance
**Dernière mise à jour :** 17 novembre 2026

## 1. Données traitées

L'application traite 2 types de données.

**Les contenus publics du subreddit r/EntreprendreEnFrance :**

- noms d'utilisateur Reddit (pseudonymes) ;
- titres, corps, flairs et scores des posts ; corps et scores des commentaires ;
- l'historique des posts de chaque membre, qui forme son « projet » dans l'app (repris d'une archive des posts publics du subreddit, puis complété au fil de l'eau) ;
- des profils d'entrepreneurs et d'entreprises, générés automatiquement à partir des posts et commentaires publics (voir § 5).

**Les données que les membres saisissent ou produisent dans l'app :**

- **le profil :** nom et logo de la boîte, secteur d'activité, compétences, région et description. Le secteur, la région et au moins 1 compétence sont demandés ; le reste est facultatif. Certains champs peuvent être préremplis d'après les messages publics du membre : ils ne sont enregistrés que s'il les valide ;
- **les quêtes :** catégorie, échéance, description modifiée et image choisies par l'auteur d'un post « Que devrais-je faire ? », pistes retenues et texte « Ce que j'ai fait » à la clôture ;
- **les pistes :** publiées en commentaire sous la quête, au nom du membre ;
- **les sondages :** la question et les réponses sont publiées en commentaire sous le post des études de marché, au nom de l'auteur. Le vote de chaque membre est enregistré avec son pseudo, pour empêcher les votes multiples ;
- **l'activité dans l'app :** points, niveaux, primes, votes du mois, parties du jeu, inscriptions aux événements ;
- **le suivi des clics :** les boutons utilisés, avec le pseudo et l'heure, pour améliorer l'app. Ce journal est effacé au bout de 60 jours.

L'application **ne collecte pas** d'adresse e-mail, de mot de passe, de coordonnées bancaires, de données de localisation précise, ni aucune donnée sensible. Elle n'utilise pas de cookie publicitaire ni de traceur.

## 2. Finalités

Les données servent uniquement au fonctionnement communautaire de l'app : quêtes et pistes, projets des membres, sondages et études de marché, classements d'activité, points et niveaux, attribution de flairs (Champion, niveaux, etc.), vote du mois, annuaire des AMA, événements et jeu.

## 3. Ce qui est visible et par qui

- Le profil s'affiche dans l'app à côté du pseudo. Le nom et le logo de la boîte présentent le projet du membre dans l'onglet Projets. Le niveau peut apparaître dans le flair du membre sur Reddit.
- Les pistes et les sondages sont publiés sur Reddit, au nom du membre, comme n'importe quel commentaire.
- La description modifiée et l'image d'une quête ne s'affichent que dans l'app.
- **Export des sondages :** l'auteur d'un sondage et les modérateurs peuvent exporter les réponses, avec pour chaque votant son pseudo, son secteur, ses compétences et sa région. Le formulaire du profil et un avertissement avant le vote le rappellent.
- L'auteur d'une quête non clôturée reçoit des rappels par modmail ; les modérateurs peuvent ensuite la clôturer.

## 4. Base légale

Intérêt légitime de l'animation de la communauté, pour les contenus déjà rendus publics par leurs auteurs sur Reddit. Pour le profil et les sondages, la saisie volontaire du membre, qui peut tout effacer à tout moment (§ 9).

## 5. Analyse automatisée (IA)

Les profils d'entrepreneurs et d'entreprises, ainsi que les champs préremplis du profil, sont produits par un outil d'analyse local qui soumet des **posts et commentaires publics** au modèle d'IA Claude (Anthropic) afin d'en extraire des résumés, catégories, secteurs et compétences. Aucune donnée privée n'est transmise. Le résultat est publié sous forme d'un fichier JSON public puis importé par l'application. Un champ prérempli n'est jamais enregistré dans le profil sans la validation du membre.

## 6. Stockage et conservation

Les données sont stockées sur l'infrastructure **Reddit / Devvit** (base Redis gérée par la plateforme). Le journal des clics est conservé 60 jours. Les profils, projets, quêtes, sondages, classements et métadonnées sont conservés tant que l'app est installée, sauf effacement demandé par le membre.

## 7. Requêtes externes

L'application récupère le fichier de profils depuis un dépôt public (`raw.githubusercontent.com`). Cette requête est en **lecture seule** : aucune donnée personnelle n'est envoyée vers ce service. Les images (logos, images des quêtes) sont envoyées par le formulaire d'image de Reddit et hébergées par Reddit.

## 8. Partage des données

Aucune donnée n'est vendue ni cédée. Aucun partage avec des tiers en dehors des prestataires d'infrastructure strictement nécessaires (Reddit/Devvit pour l'hébergement, Anthropic pour l'analyse de contenus publics), et de l'export des sondages décrit au § 3.

## 9. Vos droits

Conformément au RGPD, vous pouvez demander l'accès, la rectification ou la suppression des données vous concernant. En pratique :

- un membre modifie son profil à tout moment, ou l'efface en entier avec le bouton « Supprimer mon profil » ;
- un membre peut supprimer sur Reddit ses pistes et ses sondages publiés en commentaire ;
- un membre peut demander à être **retiré des classements**, de l'onglet Projets et de la section Profils ;
- les modérateurs disposent d'outils pour exclure un compte des classements, masquer un profil et archiver une quête.

Pour exercer ces droits, contactez l'équipe via **le modmail de r/EntreprendreEnFrance**.

## 10. Mineurs

L'application s'adresse aux utilisateurs de Reddit conformément aux conditions d'âge de Reddit. Elle ne cible pas les mineurs.

## 11. Modifications

Cette politique peut être mise à jour ; la date de dernière mise à jour ci-dessus fait foi.

## 12. Contact

Équipe de modération de r/EntreprendreEnFrance, via le modmail du subreddit.
