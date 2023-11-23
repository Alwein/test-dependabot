### Dependabot

## 1. Ce que fait Dependabot

- **Automatisation de la gestion des dépendances** : Dependabot vérifie automatiquement les dépendances de votre projet et propose des mises à jour pour assurer la sécurité et la performance.

- **Sécurité** : Il identifie les dépendances obsolètes ou vulnérables et propose des mises à jour pour réduire les risques de sécurité.

- **Mises à jour régulières** : Dependabot effectue des contrôles périodiques pour s'assurer que toutes les dépendances sont à jour.

## 2. Comment il est configuré

- **Fichier de configuration** : Dependabot utilise un fichier de configuration (.github/dependabot.yml) pour déterminer comment et quand vérifier les dépendances.

- **Personnalisation** : Vous pouvez personnaliser la fréquence des mises à jour, les répertoires à analyser, les politiques de version, etc.

- **Intégration avec GitHub** : En tant que fonctionnalité GitHub, la configuration se fait principalement via l'interface utilisateur GitHub ou le fichier de configuration dans le dépôt.

## 3. Comment il s'intègre à la pipeline

- **Intégration avec CI/CD** : Dependabot s'intègre dans les pipelines d'intégration continue (CI) et de déploiement continu (CD), en proposant des mises à jour via des Pull Requests.

- **Automatisation des tests** : Lorsqu'une mise à jour est proposée, elle peut déclencher automatiquement les pipelines de test pour s'assurer que les mises à jour n'introduisent pas de régressions.

- **Validation et fusion automatique** : Dependabot peut être configuré pour fusionner automatiquement les mises à jour après le succès des tests, facilitant la maintenance continue.

_Pour la démo: faire un push pour voir si dependabot propose une mise à jour_
