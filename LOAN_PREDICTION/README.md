# 🏦 Analyse de l'Éligibilité au Crédit Bancaire
**Projet Data Analyst - Étude de la logique décisionnelle d'octroi de prêt**

## 📌 Présentation du Projet
Ce projet consiste en une analyse exploratoire approfondie (EDA) d'un jeu de données bancaires (614 dossiers). L'objectif est d'identifier les facteurs déterminants qui influencent l'approbation d'un prêt immobilier. 

En tant que **Data Analyst**, j'ai structuré ce travail pour transformer des données brutes en insights exploitables pour une institution financière.

## 📊 Aperçu des Résultats
* **Facteur Clé :** L'historique de crédit est la variable la plus prédictive (80% de corrélation avec l'approbation).
* **Seuil de Revenu :** Identification d'un "point de bascule" à **5 000 $** de revenu total, augmentant drastiquement les chances d'accord.
* **Profil Type :** Les profils mariés et diplômés présentent un taux de validation supérieur, reflétant une stabilité recherchée par les banques.

## 🛠️ Stack Technique
* **Langage :** Python 3.x
* **Bibliothèques de Data Science :** * `Pandas` : Nettoyage et manipulation de données.
    * `Matplotlib` & `Seaborn` : Visualisations statistiques avancées (KDE Plots, Heatmaps).
* **Outils :** Jupyter Notebook, Git.

## 📂 Structure du Dépôt
* `Loan_prediction.ipynb` : Le notebook complet avec le code, les graphiques et l'interprétation.
* `Loan_data.csv` : Le dataset utilisé pour l'analyse.
* `requirements.txt` : Liste des dépendances pour reproduire l'environnement.
* `.gitignore` : Exclusion des fichiers temporaires Jupyter.

## 🚀 Installation et Utilisation
1.  **Cloner le projet :**
    git clone https://github.com/Darwing2004/Data-Analysis-Projects.git
    cd Loan-Eligibility-Analysis
    
2.  **Installer les bibliothèques nécessaires :**
    pip install -r requirements.txt

3.  **Lancer l'analyse :**
    Ouvrez le fichier `Loan_prediction.ipynb` dans Jupyter Notebook ou VS Code.

## 🏁 Conclusion & Insights Métier
L'analyse démontre que la banque privilégie la **fiabilité comportementale** (crédit passé) sur la **richesse brute**. Une recommandation majeure de ce projet est l'automatisation des dossiers "Low Risk" (Historique OK + Revenu > 5k$) pour optimiser les coûts opérationnels de la banque.

---
**Auteur :** Aipe Darwing DEGNI – www.linkedin.com/in/aipé-degni