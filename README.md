# Mamadou Rafiou Barry

**Données, systèmes distribués et intelligence artificielle** — Montréal

Finissant à la maîtrise en informatique pour la gestion intelligente des données à l'UQAM, après huit ans en TI chez un opérateur télécom : infrastructure réseau, Business Intelligence et développement logiciel.

Je cherche un **stage ou un premier poste** en ingénierie de données, science des données, intelligence artificielle ou sécurité de l'information.

---

## Projets

### [ragpipe](https://github.com/MamadouRafiou/ragpipe) — pipeline RAG distribué avec Ray

Découpage, vectorisation, index FAISS et recherche sémantique, parallélisés avec Ray. Deux backends de vectorisation derrière une interface commune, ce qui rend les 36 tests entièrement hors ligne.

Vectorisation **×1,75 sur 2 cœurs** (87 % d'efficacité parallèle). Le dépôt documente aussi une première version où Ray *ralentissait* le pipeline — une tâche par document, trop fine — et comment la mesure a mené au correctif.

`Python` · `Ray` · `FAISS` · `sentence-transformers` · `pytest`

### [nyc-taxi-eta](https://github.com/MamadouRafiou/nyc-taxi-eta) — durée des courses de taxi, inférence distribuée

Pipeline scikit-learn complet et trois modes d'inférence : pandas, Dask en mémoire, Dask hors mémoire. Générateur de données synthétiques à processus connu, ce qui permet de comparer le modèle à un plancher d'erreur théorique.

**MAE de 187,3 s pour un plancher de 185,0 s** — le modèle capte presque tout le signal apprenable. La conclusion sur Dask va à l'encontre de l'intuition, chiffres à l'appui.

`Python` · `Dask` · `scikit-learn` · `Parquet` · `pandas`

### [smartnest-ai](https://github.com/MamadouRafiou/smartnest-ai) — maison intelligente, trois paradigmes d'IA

Projet d'équipe combinant agents BDI, planification STRIPS et Random Forest. J'y ai écrit deux composants de bout en bout : **l'interpréteur de commandes en français** (100 % hors ligne, 11 actions reconnues) et **la chaîne d'intégration continue** (22 assertions, serveur Flask réellement démarré pour tester les routes).

`Python` · `Flask` · `NLP` · `GitHub Actions`

---

## Compétences

**Données et IA** — Python, SQL, scikit-learn, pandas, RAG, traitement du langage naturel, modélisation dimensionnelle, Power BI, Tableau

**Distribué et ingénierie** — Ray, Dask, Apache Spark, Parquet, Git, GitHub Actions, tests automatisés

**Systèmes et sécurité** — Active Directory, réseaux Cisco, VPN, VLAN, ISO 27001, ISO 27005, MEHARI, Loi 25

---

## Parcours

**Maîtrise en informatique pour la gestion intelligente des données** — UQAM, depuis 2025
**Baccalauréat en génie informatique** — Université Nongo, Conakry, 2012-2016

**MTN Guinée** — spécialiste Customer Value Management, ingénieur infrastructure système, agent Business Intelligence (2020-2024)

Français, anglais, arabe, peul.

---

[LinkedIn](https://www.linkedin.com/in/mamadou-rafiou-barry-97388a190/) · matrouderafiou@gmail.com
