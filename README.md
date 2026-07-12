#Simulation de Campagne de Phishing - MSHPCSUA
Objectif du projet
Ce projet consiste en la création d'un site web répliquant l'interface du portail du Ministère de la Santé, de l'Hygiène Publique, de la Couverture Sanitaire Universelle et des Assurances (MSHPCSUA) de la République Togolaise.

Note importante : Ce site a été développé exclusivement dans un cadre pédagogique et de recherche en cybersécurité. L'objectif est de simuler des techniques d'ingénierie sociale afin d'étudier les vecteurs d'attaque par phishing, d'évaluer la sensibilisation aux risques numériques et de tester des mesures de défense dans un environnement strictement contrôlé.

⚠️ Avertissement Éthique et Légal
Usage Éducatif uniquement : Ce contenu ne doit, sous aucun prétexte, être utilisé à des fins malveillantes ou pour tromper des utilisateurs réels sans leur consentement explicite.

Environnement Contrôlé : Toutes les activités liées à ce projet ont été menées sur des infrastructures isolées.

Responsabilité : L'auteur décline toute responsabilité quant à une utilisation inappropriée de ce code en dehors du cadre de la recherche en cybersécurité.

🛠️ Stack Technique
Frontend : HTML5, Tailwind CSS

Framework de déploiement : Netlify (utilisé pour la gestion des soumissions de formulaires dans le cadre du test de simulation)

Outils de développement : Netlify CLI

Installation & Développement local
Pour tester la simulation dans votre environnement local :

Bash
# Cloner le projet
git clone https://github.com/ton-compte/ton-repo.git
cd ton-repo

# Installer Netlify CLI
npm install -g netlify-cli

# Lancer le serveur local
netlify dev
Le site sera accessible sur http://localhost:8888.

Note : L'utilisation de netlify dev est requise pour tester correctement la capture des données de formulaires.

Méthodologie de Simulation
Le site intègre un formulaire de collecte de données configuré via les fonctionnalités "Forms" de Netlify. Cette configuration permet de mesurer :

Le taux de clic (interaction avec l'interface).

La propension des utilisateurs cibles à soumettre des données sensibles dans un formulaire de type "inscription" ou "newsletter" sans vérification préalable de l'URL.

 Objectifs de Sensibilisation
Ce projet permet d'illustrer concrètement les points suivants lors de sessions de formation :

L'importance de vérifier l'URL d'un site avant toute interaction.

La reconnaissance des signes de spoofing (usurpation d'identité visuelle).

La nécessité de ne jamais soumettre d'identifiants sur des plateformes non officielles.

 Licence
Projet de recherche en cybersécurité — © 2026.
Ce projet n'est pas lié au Ministère de la Santé de la République Togolaise et ne constitue en aucun cas une communication officielle de ladite institution.
