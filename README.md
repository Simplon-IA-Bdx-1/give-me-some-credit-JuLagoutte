# give-me-some-credit-JuLagoutte
give-me-some-credit-JuLagoutte created by GitHub Classroom
Machine Learning Project - Competition Kaggle

## Pré-requis
* Docker ou Anaconda
* Python
* Big ML
* Kaggle

## Usages
* Avec `git clone`, récupérer le repo en locale sur votre laptop
* Pour le fichier `auth.env`, reprendre le `auth-sample.env`, le renommer et remplacer par vos identifiants et vos mots de passe 
* Créer le fichier `requirements.txt` avec tous les packages dont vous aurez besoin pour exécuter les notebooks
* Une fois tous les dossiers et fichiers créés, en ligne de commande, se positionner dans le dossier `docker`
* Puis lancer une commande `docker-compose up` pour démarrer le container.

* Récupérer l'adresse url avec le token dans la console
* Coller l'adresse url dans la barre de votre navigateur

Vous allez retrouver tous vos notebooks et dossiers contenus dans ce repo

## Fichiers
* [GiveMeCredit_SubmissionKaggle_BigML.ipynb](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-JuLagoutte/blob/master/GiveMeCredit_SubmissionKaggle_BigML.ipynb) : notebook pour faire une submission à Kaggle via l'API BigML
* [GiveMeCredit_Xgboost_Sklearn.ipynb](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-JuLagoutte/blob/master/GiveMeCredit_Xgboost_Sklearn.ipynb) : notebook pour faire submission à Kaggle en utilisant Scikit-learn ou XGBoost
* [Exercice_1input_prediction.ipynb](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-JuLagoutte/blob/master/Exercice_1input_prediction.ipynb) : notebook pour prédire sur un nouvel input donné avec les 3 méthodes utilisées

* [GiveMeCredit_ModelReview.ipynb](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-JuLagoutte/blob/master/GiveMeCredit_ModelReview.ipynb) : notebook pour analyser notre dataset, notre modèle et nos résultats
* [GiveMeCredit_ContinuousImprovement.ipynb](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-JuLagoutte/blob/master/GiveMeCredit_ContinuousImprovement.ipynb) : notebook l'amélioration continue de notre dataset, notre modèle et nos résultats

* [GiveMeCredit_LearningCurves.ipynb](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-JuLagoutte/blob/master/GiveMeCredit_LearningCurves.ipynb) : notebook pour visualiser les courbes d'apprentissage de notre dataset

## Scores Kaggle :

| Méthode                          |  Public Score  |  Private Score |
| :------------------------------- | :-------------:| -------------: |
| Big ML - Ensemble                |     0.85929    |        0.86452 |
| XGBoost - Classifier             |     0.86035    |        0.86655 |
| Sklearn - RandomForestClassifier |     0.78032    |        0.78227 |

@Julien Lagoutte
