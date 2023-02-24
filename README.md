# Machine Learning Portfolio
	
Voici mon Portfolio contenant des projets de Machine Learning/ Data Science que j'ai pu réaliser. Ils ont été réalisé dans le cadre d'une formation "Ingénieur Machine Learning" d'Openclassrooms que je viens de finaliser. Ce parcours de formation est réalisé en partenariat avec l’ENSAE-ENSAI. 
Ce parcours d'Openclassrooms en partenariat avec CentraleSupélec est constitué de ces huits projets ci-dessus. La finalité est l'obtention un titre "Data scientist" de type RNCP:

Projet 1 : Définissez votre stratégie d'apprentissage

Projet 2 : Concevez une application au service de la santé publique

Projet 3 : Anticipez les besoins en consommation électrique de bâtiments

Projet 4 : Segmentez des clients d'un site e-commerce

Projet 5 : Catégorisez automatiquement des questions

Projet 6 : Classez des images à l'aide d'algorithmes de Deep Learning

Projet 7 : Développez une preuve de concept (Segmentation d'images sous-marines)

Projet 8 : Participez à une compétition Kaggle
	
	
## [Projet: Concevez une application au service de la santé publique](https://github.com/Bounkass/P2_OC_Parcours_IML)
L'agence "Santé publique France" a lancé un appel à projet autour des problématiques alimentaires. Vous proposerez une application basée sur des données nutritionnelles.


### Compétences développées:

- Effectuer des opérations de nettoyage sur des données structurées

- Effectuer une analyse statistique univariée et multivariée

L'application proposée **nutri-vegan** permet d'abord de savoir si un aliment convient pour un régime végétarien ou végitalien, en fonction des ingrédients d'orogine animale contenants dans le produit. Cette étape est réalisée uns fois scanner le code-barres du produit. En suite l'application propose le score nutritinelle du produits vegan, détaille ses ingrédients et estime sa composition nutritionnelles, notamment les micro-nutriments. L'application ainsi peut recommander d'autre produits de la même famille qui contient plus de teneur en macro et micro-nutriments notamment le fer le calcium et de la vitamine c.

<p float="left">
  <img src="https://github.com/Bounkass/ML_Portfolio/blob/main/images/appli2.png" width="44%" height="55%"/>
  <img src="https://github.com/Bounkass/ML_Portfolio/blob/main/images/Mcorr.png" width="54%" height="65%"/>	
</p>


## [Projet: Anticipez les besoins en consommation électrique de bâtiments](https://github.com/Bounkass/P3_OC_Parcours_IML)

La ville de Seatlle veut atteindre son objectif ambitieux d'une ville neutre en émissions de carbone en 2050. Elle s’intéresse de près aux émissions des bâtiments non destinés à l’habitation. Des relevés minutieux ont été effectués par des agents experts en 2015 et en 2016. Cependant, ces relevés sont coûteux à obtenir pour chaque année, ainsi en se basant sur ceux déjà réalisés, la ville souhaite dans un premier temps de:

- Prédire les émissions de Co2 et la consommation totale de l'énergie des bâtiments pour lesquels elles n’ont pas encore été mesurées.
- Evaluer l'influence de feature Star Energy Score sur les prédictions.
Source des données : https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv

### Contenu des  livrables:
- Préparation des données 
- Entraînement de différents algorithmes de machine learning (Regresion linéaire, SVR, XGBoost, Random Forest Regressor)
- Optimisation des hyperparamètres
- Recherche d'importance des features
- Mise en oeuvre du modèle optimal pour la  prédiction de consommation et émissions de C02
- Evaluation de  l'influence de feature Star Energy Score sur les prédictions

<p align="center">
  <img src="https://github.com/Bounkass/ML_Portfolio/blob/main/images/city_seattle.png" width="65%" height="45%">
</p>
<p align="center">
  <img src="https://github.com/Bounkass/ML_Portfolio/blob/main/images/GBR_RFR.png">
</p>
