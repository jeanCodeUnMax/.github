# Politique de securite

## Signaler une vulnerabilite

Merci de **ne pas** ouvrir d'issue publique pour une faille de securite.

Options de signalement prive :

1. **GitHub Private Vulnerability Reporting** : onglet *Security* > *Report a vulnerability* (si active sur le repo)
2. **GitHub Security Advisories** via l'interface du depot

## Delais de reponse

- Accuse de reception : sous 7 jours
- Evaluation initiale : sous 30 jours

## Versions supportees

Seule la derniere version de la branche par defaut recoit des correctifs de securite.

## Mesures automatisees

Les depots de ce compte utilisent :

- Dependabot (alertes de vulnerabilites + mises a jour de securite automatiques)
- Secret scanning + push protection (depots publics)
- Code scanning CodeQL (depots publics)
- CI tests unitaires via GitHub Actions
