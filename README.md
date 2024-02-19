# Databricks-Accidents-Project

Dans le cadre de ce projet, l'objectif était de prendre en main différents outils tels que Azure, Github, et DataBricks.

Azure a été utilisé pour créer un groupe de ressources dans lequel nous avons travaillé et trouvé notre module DataBricks.

Sur Databricks, l'objectif était de consolider trois modèles de Machine Learning :

1. KNeighborsClassifier
2. DecisionTreeClassifier
3. RandomForestClassifier

Les étapes comprenaient l'importation des données, la préparation des échantillons d'apprentissage et de test, la création des modèles avec optimisation des paramètres via `GridSearchCV`, et enfin, l'évaluation des performances.

Le modèle retenu est le suivant :

**Random Forest**

**Performances :**
- Recall: 0.367
- F1-Score: 0.345

Le lien de l'endpoint est le suivant :

[BestModel Endpoint](https://adb-6256268981679381.1.azuredatabricks.net/serving-endpoints/BestModel/invocations)



## Repository GitHub

Le repository est accessible [ici : Databricks-Accidents-Project](https://github.com/UkiSSa/Databricks-Accidents-Project). Les éléments inclus sont :

1. Deux notebooks Databricks au format `dbc`.
2. Un fichier README.md documenté avec :
    - Présentation du projet
    - Sources des données (cf: [Ilyes Talbi](https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/))
    - Informations sur le modèle retenu et ses performances
    - Lien de l'endpoint du modèle

## Liens Utiles

- [Assigner un rôle à un utilisateur](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal?tabs=delegate-condition)
- [Tutoriel d'Ilyes Talbi de la revue IA](https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/)
- [Limitation des régions dans Databricks](https://learn.microsoft.com/en-us/azure/databricks/machine-learning/model-serving/model-serving-limits)
- [Création d'un token avec Databricks](https://docs.databricks.com/en/dev-tools/cli/authentication.html)
- [Création d'un endpoint avec Databricks](https://docs.databricks.com/en/machine-learning/model-serving/create-manage-serving-endpoints.html)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [GitHub Get Started](https://docs.github.com/fr/get-started/quickstart/hello-world)
- [Plus d'info sur la commande GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
