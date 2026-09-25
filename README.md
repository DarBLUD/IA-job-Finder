# IA Job Finder

<div align="center">

**Trouvez moins d'offres. Trouvez les bonnes.**

Une vitrine moderne pour une expérience de recherche d'emploi assistée par l'IA.

[Découvrir la démo](./index.html) · [Signaler une idée](https://github.com/DarBLUD/IA-job-Finder/issues)

</div>

---

## Pourquoi IA Job Finder ?

La recherche d'emploi ne devrait pas être une course aux onglets ouverts. IA Job Finder est un concept d'assistant qui aide les candidats à transformer une veille dispersée en opportunités réellement pertinentes.

- **Des résultats personnalisés** selon le métier, les compétences et la localisation ;
- **Un tri intelligent** pour réduire le bruit et se concentrer sur les offres utiles ;
- **Une veille plus sereine** pour ne pas passer à côté de la bonne opportunité ;
- **Une expérience claire** pensée pour les emplois, alternances et stages.

## Fonctionnement

1. **Définissez votre projet** — indiquez vos objectifs, compétences et préférences.
2. **Laissez l'assistant analyser** — les offres sont regroupées et priorisées selon votre profil.
3. **Passez à l'action** — consultez les meilleures correspondances et préparez vos candidatures.

## Aperçu

Le projet inclut une landing page responsive, sans framework ni dépendance, qui présente le produit et ses bénéfices.

![Aperçu de la landing page IA Job Finder](./assets/preview.svg)

## Installation et lancement

Aucune installation complexe n'est nécessaire pour découvrir la vitrine :

```bash
git clone https://github.com/DarBLUD/IA-job-Finder.git
cd IA-job-Finder
```

Ouvrez ensuite `index.html` dans votre navigateur, ou lancez un serveur local :

```bash
python3 -m http.server 8000
```

Puis rendez-vous sur [http://localhost:8000](http://localhost:8000).

> **État du projet :** la version actuelle est une vitrine/prototype de l'expérience IA Job Finder. Le moteur de collecte, de classement et de recommandations est prévu dans les prochaines étapes.

## Feuille de route

- [x] Landing page responsive et accessible
- [x] Présentation du parcours en trois étapes
- [x] Section bénéfices et appel à l'action
- [ ] Connexion à des sources d'offres d'emploi
- [ ] Création et sauvegarde d'un profil candidat
- [ ] Matching intelligent entre profil et offres
- [ ] Notifications et tableau de suivi des candidatures

## Structure

```text
.
├── index.html       # Page d'accueil
├── styles.css       # Design responsive, sans dépendance
├── assets/
│   └── preview.svg  # Illustration de présentation
└── README.md
```

## Contribuer

Une idée pour rendre la recherche d'emploi plus simple ? Les contributions sont les bienvenues :

1. créez une *issue* pour discuter de votre idée ;
2. créez une branche dédiée ;
3. proposez une pull request avec une description claire.

## Licence

La licence sera précisée lorsque le moteur fonctionnel sera publié. En attendant, le contenu de ce dépôt est présenté à des fins de démonstration.
