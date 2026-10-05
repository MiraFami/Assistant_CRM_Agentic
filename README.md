# Assistant CRM Agentique


## 📌 Présentation

Application Streamlit développée dans le cadre de mon stage chez AVISIA.

L'application transforme une intention de campagne marketing exprimée
en langage naturel en une campagne complète, construite progressivement
avec l'utilisateur.

## 🎯 Fonctionnalités

- Segmentation des clients
- Génération de requêtes SQL
- Génération d'objets d'email
- Génération de corps d'email
- Génération de visuels
- Produits complémentaires
- Mises en situation
- Assemblage de la campagne

## 🧠 Fonctionnement

1. L'utilisateur décrit son intention de campagne.
2. L'application propose trois segments.
3. L'utilisateur sélectionne un segment.
4. L'IA propose plusieurs objets d'email.
5. L'IA génère le corps du message.
6. Un visuel est généré selon la charte choisie.
7. La campagne finale est assemblée.

## 🛠️ Technologies

- Python
- Streamlit
- Pandas
- DuckDB
- Google Gemini / Vertex AI
- SQL

## 👩‍💻 Mon rôle

- Conception et développement de l'application
- Mise en place du parcours de création de campagne
- Travail sur la segmentation client
- Intégration des modèles d'IA
- Génération et adaptation des contenus marketing
- Développement de l'interface Streamlit

## 📸 Présentation du projet

La présentation du projet réalisé durant mon stage est disponible ici :

[Voir la présentation](Présentation_Projet/AVISIA_Projet_CRM_Agentic_Google_Slides.pdf)

---

## Structure du projet

```
crm_agentic/
├── 📁 .streamlit/             Configuration de Streamlit (config.toml)
├── 📁  assets/                Ressources (logos, favicon, images fixes)
├── 📁  data/                  Données utilisées par l'application
├── 📁  prompts/               Templates de prompts (segments, email, visuels)
├── 📁  app.py                 Application Streamlit (interface + parcours)
├── 📁  service_segment.py     Génération des segments (text-to-SQL, DuckDB)
├── 📁  service_email.py       Génération des objets et corps d'email
├── 📁  service_visuel.py      Génération des visuels + mises en situation
├── 📁  service_produits.py    Produits complémentaires + vignettes
├── 📁  requirements.txt       Dépendances Python
└── 📁  README.md              Presentation et dependances
```

