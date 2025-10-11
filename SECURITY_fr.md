# Politique de Sécurité

> 🌍 **Autres langues** : [English](SECURITY.md)

## 🔒 Notre Engagement

La Mauritania Programmers Community prend très au sérieux la sécurité de nos projets et de notre communauté. Nous apprécions vos efforts pour divulguer de manière responsable les vulnérabilités de sécurité.

---

## 🛡️ Versions Supportées

Nous fournissons des mises à jour de sécurité pour les versions suivantes :

| Version | Supportée          |
| ------- | ------------------ |
| Dernière  | ✅ Supportée       |
| Anciennes   | ⚠️ Au mieux     |

---

## 🚨 Signaler une Vulnérabilité

### Comment Signaler

Si vous découvrez une vulnérabilité de sécurité, veuillez suivre ces étapes :

#### 1. **NE CRÉEZ PAS** d'Issue Publique
Les vulnérabilités de sécurité ne doivent PAS être signalées via les issues GitHub publiques.

#### 2. Signaler en Privé

**Méthode Préférée** : Utilisez les Avis de Sécurité GitHub
- Accédez à l'onglet Sécurité du dépôt
- Cliquez sur « Signaler une vulnérabilité »
- Remplissez le formulaire de rapport de vulnérabilité

**Méthodes Alternatives** :
- Envoyer un email aux administrateurs de l'organisation (coordonnées disponibles sur notre LinkedIn)
- Message direct sur LinkedIn : [@مبرمجي-موريتانيا](https://linkedin.com/company/مبرمجي-موريتانيا)

#### 3. Inclure Ces Détails

Pour nous aider à comprendre et résoudre le problème rapidement, veuillez inclure :

- **Type de vulnérabilité** (ex: XSS, injection SQL, contournement d'authentification)
- **Emplacement** (chemin du fichier, URL, ou composant affecté)
- **Reproduction étape par étape** (comment reproduire le problème)
- **Évaluation de l'impact** (ce qu'un attaquant pourrait faire)
- **Correctif suggéré** (si vous avez des recommandations)
- **Vos coordonnées** (pour les questions de suivi)

### À Quoi S'Attendre

1. **Accusé de Réception** : Sous 48 heures
2. **Évaluation Initiale** : Sous 1 semaine
3. **Mises à Jour de Statut** : Communication régulière tout au long du processus
4. **Délai de Résolution** : Dépend de la gravité
   - 🔴 Critique : 1-7 jours
   - 🟠 Élevé : 1-2 semaines
   - 🟡 Moyen : 2-4 semaines
   - 🟢 Faible : Au mieux

---

## 🏆 Reconnaissance

### Temple de la Renommée Sécurité

Nous reconnaissons les chercheurs en sécurité qui nous aident à maintenir la sécurité de notre communauté :

- Reconnaissance publique (avec permission)
- Inscription dans notre Temple de la Renommée Sécurité
- Reconnaissance dans les notes de version
- Appréciation de la communauté

### Divulgation Responsable

Nous suivons les principes de divulgation responsable :
- Nous travaillerons avec vous pour comprendre et résoudre le problème
- Nous ne poursuivrons pas en justice la recherche de sécurité de bonne foi
- Nous vous créditerons pour la découverte (sauf si vous préférez rester anonyme)

---

## 🔐 Meilleures Pratiques de Sécurité

### Pour les Contributeurs

Lors de la contribution de code, veuillez :

1. **Ne Jamais Commiter de Secrets**
   - Pas de clés API, mots de passe ou tokens dans le code
   - Utilisez des variables d'environnement pour les données sensibles
   - Vérifiez avec des outils comme [git-secrets](https://github.com/awslabs/git-secrets)

2. **Suivre les Pratiques de Codage Sécurisé**
   - Valider et assainir toutes les entrées
   - Utiliser des requêtes paramétrées (prévenir l'injection SQL)
   - Implémenter une authentification et autorisation appropriées
   - Maintenir les dépendances à jour

3. **Examiner les Implications de Sécurité**
   - Considérer l'impact sécuritaire de vos modifications
   - Demander aux mainteneurs en cas de doute
   - Documenter le code sensible à la sécurité

### Pour les Utilisateurs

Pour garder vos projets sécurisés :

1. **Maintenir les Logiciels à Jour**
   - Utiliser les dernières versions stables
   - Appliquer rapidement les correctifs de sécurité
   - Surveiller les avis de sécurité

2. **Utiliser une Authentification Forte**
   - Activer la 2FA sur votre compte GitHub
   - Utiliser des mots de passe forts et uniques
   - Protéger vos clés SSH

3. **Être Prudent**
   - Examiner le code avant de l'exécuter
   - Ne pas partager d'identifiants
   - Signaler toute activité suspecte

---

## 🛠️ Outils et Ressources de Sécurité

### Sécurité Automatisée

Nous utilisons divers outils pour maintenir la sécurité :

- **Dependabot** : Mises à jour automatiques des dépendances
- **CodeQL** : Analyse de code sécurité
- **Analyse de Secrets** : Détection des secrets committés
- **Avis de Sécurité** : Suivi des CVE

### Ressources

En savoir plus sur la sécurité :

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Meilleures Pratiques de Sécurité GitHub](https://docs.github.com/fr/code-security)
- [CWE - Common Weakness Enumeration](https://cwe.mitre.org/)
- [CVE - Common Vulnerabilities and Exposures](https://cve.mitre.org/)

---

## 📋 Politique de Divulgation de Vulnérabilités

### Portée

Cette politique de sécurité s'applique à :

- Tous les dépôts sous l'organisation Mauritania Programmers Community
- L'infrastructure officielle de la communauté
- Les outils et services maintenus par la communauté

### Hors de Portée

Les éléments suivants sont généralement hors de portée :

- Vulnérabilités dans les services tiers que nous ne contrôlons pas
- Attaques d'ingénierie sociale contre les membres de la communauté
- Problèmes de sécurité physique
- Attaques par déni de service (DoS)

En cas de doute, veuillez le signaler quand même. Nous déterminerons la portée.

---

## 🚫 Ce qu'il Ne Faut PAS Faire

Veuillez NE PAS :

- Accéder ou modifier des données qui ne vous appartiennent pas
- Effectuer des attaques par déni de service (DoS)
- Spammer ou faire de l'ingénierie sociale sur les membres de la communauté
- Violer la vie privée des membres de la communauté
- Endommager ou perturber les services
- Divulguer publiquement les vulnérabilités avant résolution

---

## 📞 Contact

Pour les questions ou préoccupations liées à la sécurité :

- **Problèmes de Sécurité** : Utilisez les Avis de Sécurité GitHub
- **Questions Générales de Sécurité** : GitHub Discussions (catégorie Sécurité)
- **Affaires Urgentes** : LinkedIn [@مبرمجي-موريتانيا](https://linkedin.com/company/مبرمجي-موريتانيا)

---

## 📜 Politique de Mise à Jour de Sécurité

### Communication

Les mises à jour de sécurité seront communiquées via :

1. **Avis de Sécurité GitHub**
2. **Notes de Version**
3. **Annonces GitHub Discussions**
4. **Mises à Jour LinkedIn**

### Versioning

Les correctifs de sécurité seront :
- Publiés en tant que versions de patch pour les vulnérabilités mineures
- Publiés en tant que mises à jour d'urgence pour les vulnérabilités critiques
- Documentés dans le CHANGELOG avec des labels de sécurité

---

## 🙏 Merci

Nous apprécions la communauté de recherche en sécurité et tous les contributeurs qui aident à garder nos projets sécurisés.

Votre divulgation responsable aide à protéger :
- 🇲🇷 La communauté des développeurs mauritaniens
- 🌍 Les utilisateurs de nos projets dans le monde entier
- 💻 L'écosystème open source au sens large

---

<div align="center">

**Protection de l'Avenir Technologique de la Mauritanie 🇲🇷💻🔒**

Fait avec ❤️ par la communauté technologique mauritanienne

[Signaler une Vulnérabilité](../../security/advisories/new) • [Directives de Sécurité](https://docs.github.com/fr/code-security)

</div>
