---
layout: default
title: "Politique de confidentialité"
---

# Politique de confidentialité — Bodycount

**Version** : 1.0  
**Dernière mise à jour** : 25 octobre 2026  
**Responsable du traitement** : Benjamin Merlet, auto-entrepreneur, France  
**Contact** : contact@shadowappstudio.com

*English version: [Privacy Policy](privacy-policy.html)*

---

## 1. L'essentiel

- **Vos données intimes restent sur votre téléphone.** Partenaires, dates, notes, commentaires, photos, villes et préférences sont enregistrés uniquement sur votre appareil. L'Éditeur n'y a pas accès, et l'Application ne les envoie ni à ses serveurs ni à Google.
- **Un compte n'est créé que pour Premium** (adresse e-mail, mot de passe, mois et année de naissance).
- **La version gratuite affiche une bannière publicitaire** (Google AdMob). Les annonces ne sont pas personnalisées. Dans l'Espace économique européen, au Royaume-Uni et en Suisse, un formulaire vous demande d'abord votre consentement.
- **Premium n'affiche aucune publicité** : le module publicitaire n'est même pas démarré.
- **L'Application est réservée aux personnes majeures** (18 ans et plus).

---

## 2. Qui est responsable de vos données ?

Bodycount (« l'Application ») est éditée par **Benjamin Merlet**, auto-entrepreneur domicilié en France (« l'Éditeur »). Il est responsable du traitement des données décrites ci-dessous, à l'exception de celles que traitent Google et Stripe pour leur propre compte (voir §3.3 et §3.4).

Pour toute question ou pour exercer vos droits : **contact@shadowappstudio.com**.

---

## 3. Données traitées, finalités et bases légales

### 3.1 Données saisies dans l'Application

Elles concernent votre vie intime, donc de nature particulièrement sensible : nom ou pseudonyme des partenaires, notes, commentaires, taille, sexe, ethnicité, pratiques (« kinks »), ville, dates et durées des rencontres, photos.

- Elles sont stockées **uniquement sur votre appareil**, dans l'espace privé de l'Application.
- L'Éditeur **ne les collecte pas, ne peut pas les lire et ne les transmet à personne**. Aucune de ces données n'est envoyée à Google, à Stripe ni à un autre tiers par l'Application.
- L'accès à l'Application est protégé par un **code PIN à 4 chiffres**, dont seule l'empreinte (SHA-256) est conservée sur l'appareil.
- La **caméra** et la **galerie** ne sont utilisées que lorsque vous ajoutez une photo ; la photo est copiée dans l'espace privé de l'Application.
- Elles sont exclues des sauvegardes automatiques d'Android (voir §9).

### 3.2 Compte Premium (serveur)

| Donnée | Pourquoi | Base légale |
|---|---|---|
| Adresse e-mail (en minuscules) | Créer et identifier votre compte, vous connecter, rattacher votre abonnement | Exécution du contrat (art. 6.1.b RGPD) |
| Mot de passe, conservé uniquement sous forme d'empreinte (bcrypt) | Authentification | Exécution du contrat |
| Mois et année de naissance | Vérifier que vous avez 18 ans ou plus | Intérêt légitime de réserver l'Application aux majeurs (art. 6.1.f) |
| Langue choisie | Afficher l'Application dans votre langue | Exécution du contrat |
| Identifiant client Stripe, statut et dates de l'abonnement | Gérer l'abonnement et ses renouvellements | Exécution du contrat |
| Date de création du compte | Gestion du compte | Exécution du contrat |

Un jeton de connexion (valable 30 jours) est stocké sur votre appareil. Le serveur est hébergé par Railway (États-Unis).

### 3.3 Paiement (Stripe)

Le paiement de Premium se fait sur une **page hébergée par Stripe**. Vos données de carte bancaire sont saisies chez Stripe et **ne sont jamais accessibles à l'Éditeur**. L'Éditeur transmet à Stripe votre adresse e-mail pour créer votre fiche client. Stripe traite ensuite vos données de paiement en tant que prestataire de paiement, selon sa propre politique de confidentialité : <https://stripe.com/privacy>.

### 3.4 Publicité (Google AdMob) — version gratuite uniquement

La version gratuite affiche une bannière fournie par **Google AdMob** (Google Ireland Limited pour l'Espace économique européen, Google LLC ailleurs). Pour la diffuser, le module publicitaire de Google collecte automatiquement, depuis votre appareil :

- votre adresse IP ;
- l'identifiant publicitaire Android (ou un identifiant propre à l'application s'il est désactivé) ;
- des informations sur l'appareil et l'Application : modèle, version d'Android, langue, taille d'écran, version de l'Application ;
- des événements liés aux annonces : affichage, clic, erreur de chargement.

Ce que cela implique :

- **Les annonces ne sont pas personnalisées** : elles ne sont pas ciblées selon vos centres d'intérêt, et l'Application limite le contenu des annonces (pas d'annonces pour public adulte).
- **Nous ne transmettons à Google aucune donnée saisie dans l'Application** (partenaires, dates, photos, notes, villes, etc.).
- En revanche, le simple fait que Google reçoive des informations techniques depuis cette Application lui permet de savoir qu'elle est installée sur votre appareil. Si cela vous gêne, passez à Premium : aucune donnée n'est alors envoyée à Google pour la publicité.
- Google agit comme **responsable de traitement distinct** pour ses finalités publicitaires et de sécurité. Voir <https://policies.google.com/technologies/partner-sites> et <https://policies.google.com/privacy>.
- **Base légale :** votre **consentement** (art. 6.1.a RGPD et directive ePrivacy), recueilli par un formulaire de Google dans l'Espace économique européen, au Royaume-Uni et en Suisse. Dans les autres régions, l'intérêt légitime de financer l'Application gratuite, dans le respect de la loi locale.

### 3.5 Carte et position (Premium)

L'écran Carte demande l'autorisation d'accéder à votre **position approximative**. Elle sert uniquement à centrer la carte sur vous, **sur votre appareil** : elle n'est pas envoyée à l'Éditeur. L'affichage de la carte fait appel à **Google Maps**, qui reçoit des informations techniques (adresse IP, appareil, zone affichée) selon <https://policies.google.com/privacy>. Vous pouvez refuser ou retirer l'autorisation dans les réglages d'Android ; la carte n'est alors pas disponible.

### 3.6 Recherche de ville (Premium)

Lorsque vous cherchez une ville pour un partenaire, **le texte que vous tapez** (et votre adresse IP) est envoyé au service de géocodage **Photon, exploité par Komoot GmbH** (Allemagne), qui renvoie des suggestions. Seul ce texte est transmis : il n'est pas relié au nom du partenaire ni à vos autres données. Base légale : exécution du contrat (la fonction que vous utilisez).

### 3.7 Journaux techniques

L'hébergeur du serveur (Railway) peut enregistrer des journaux techniques (adresse IP, date, requête) pour assurer la sécurité et le fonctionnement du service. L'Éditeur n'utilise aucun outil d'analyse d'audience ni de rapport de plantage, en dehors du module publicitaire décrit au §3.4.

---

## 4. Publicité : vos choix

- **Consentement (Espace économique européen, Royaume-Uni, Suisse).** Un formulaire s'affiche avant la première annonce. Vous pouvez refuser : l'Application reste utilisable.
- **Modifier votre choix à tout moment** : *Options* (icône d'engrenage) → **Confidentialité publicitaire**. Cette ligne n'apparaît que si votre région l'impose.
- **Identifiant publicitaire** : vous pouvez le réinitialiser ou le supprimer dans les réglages d'Android (rubrique *Confidentialité* ou *Google* → *Annonces*, selon la version).
- **Supprimer la publicité** : l'abonnement Premium retire la bannière.

---

## 5. Destinataires

| Destinataire | Rôle | Données | Pays |
|---|---|---|---|
| Railway | Hébergement du serveur (sous-traitant) | Données du compte Premium (§3.2), journaux techniques | États-Unis |
| Stripe | Paiement | E-mail, données de paiement (saisies chez Stripe) | États-Unis, Union européenne |
| Google (AdMob) | Publicité (version gratuite) | Données techniques (§3.4) | États-Unis, Irlande |
| Google (Maps) | Affichage de la carte (Premium) | Données techniques (§3.5) | États-Unis, Irlande |
| Komoot (Photon) | Recherche de ville (Premium) | Texte saisi, adresse IP (§3.6) | Allemagne |

L'Éditeur ne vend pas vos données et ne les communique à aucun autre tiers.

---

## 6. Transferts hors de l'Union européenne

Railway, Stripe et Google peuvent traiter des données aux États-Unis. Ces transferts reposent, selon le prestataire, sur le **cadre de protection des données UE–États-Unis** (Data Privacy Framework) ou sur les **clauses contractuelles types** de la Commission européenne.

---

## 7. Durées de conservation

| Donnée | Durée |
|---|---|
| Données saisies dans l'Application | Sur votre appareil, jusqu'à ce que vous les supprimiez ou désinstalliez l'Application |
| Compte Premium (§3.2) | Tant que le compte est actif ; suppression dans les 30 jours suivant votre demande |
| Justificatifs de paiement | 10 ans (obligation comptable) |
| Données publicitaires | Selon la politique de Google |
| Choix de consentement publicitaire | Sur votre appareil, jusqu'à ce que vous le modifiiez ou désinstalliez l'Application |

---

## 8. Sécurité

- Les échanges avec le serveur passent par une connexion chiffrée (HTTPS).
- Les mots de passe ne sont jamais conservés en clair (empreinte bcrypt).
- L'accès à l'Application est protégé par un code PIN, et les données sont dans l'espace privé de l'Application, protégé par le chiffrement de votre appareil lorsqu'il est activé.
- Vous restez responsable de la sécurité de votre téléphone (verrouillage de l'écran, mises à jour).

---

## 9. Sauvegarde Android

L'Application demande à Android de **ne pas inclure ses données dans les sauvegardes automatiques** (compte Google) ni dans les transferts vers un nouvel appareil. Vos données restent donc sur ce seul appareil.

**Conséquence : si vous changez de téléphone ou désinstallez l'Application, vous perdez vos données locales.** L'Éditeur ne peut pas les récupérer.

---

## 10. Vos droits

Conformément au RGPD, vous disposez des droits d'**accès**, de **rectification**, d'**effacement**, de **limitation**, de **portabilité** (pour les données de votre compte) et d'**opposition**, ainsi que du droit de **retirer votre consentement** à tout moment, sans que cela n'affecte les traitements passés.

- **Comment les exercer** : écrivez à **contact@shadowappstudio.com**. L'Éditeur répond dans un délai d'un mois. Une pièce justificative peut être demandée en cas de doute sur votre identité.
- **Données de l'Application** : elles sont sur votre appareil. Vous les consultez, modifiez et supprimez directement dans l'Application, ou en la désinstallant.
- **Données de Google et de Stripe** : adressez-vous directement à ces sociétés.
- **Réclamation** : vous pouvez saisir la CNIL (Commission nationale de l'informatique et des libertés) : <https://www.cnil.fr/fr/plaintes>.

---

## 11. Mineurs

L'Application est **strictement réservée aux personnes majeures**. L'Éditeur ne collecte pas sciemment de données concernant des mineurs. S'il apprend qu'un compte appartient à un mineur, il le supprime.

---

## 12. Modifications

Cette politique peut évoluer, par exemple si une fonction ou un prestataire change. La version en vigueur est celle publiée à l'adresse indiquée dans la fiche de l'Application, avec sa date de mise à jour. Tout changement important vous est signalé dans l'Application.

---

*Dernière mise à jour : 25 octobre 2026*
