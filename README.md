# House_Predict_Amesterdam_Lille
Si vous êtes comme moi, vous pourriez être débordé lorsque vous devez prendre de grandes décisions telles que l'achat d'une maison. Dans de tels cas, j'aime toujours opter pour une approche axée sur les données, qui m'aidera à trouver une solution optimale. Cela implique deux étapes. Premièrement, nous devons rassembler autant de données que possible. Deuxièmement, nous devons définir une métrique de réussite.

La collecte des prix des logements demande un certain effort. Une mise en garde est que les prix demandés ne sont pas les prix auxquels les maisons ont été réellement vendues. Définir un indicateur de réussite est quelque peu subjectif. Je considère qu'une maison est une bonne option si le prix de la maison est bon marché par rapport aux autres annonces de la région.

le but de ce projet c'etait de predire le prix d'un bien immobilier dans la ville de lille et amesterdam
# house_price_predict_amsterdam

Demarche de travail 

exploration de donnees:

Analyse de form (type variable,etudes de valeures manquantes , visualisation variable cile(Price) 
Analyse de fond(visualisation de variables (zip,area,room,lan,lon), etude de relation target/variables,etude de relation varaible/variable )

preprocessing:

Imputation de donnees , standarisation de donnees, repartition et recuperation des données preparés)

premire_modele( entrainement d'un premier modele de regression(LinearRegression) , etude des learning curve )

Regression:

evaluation de differentes modeles(Support Vector Regressor, LogisticRegression,DecisionTreeRegression,KNeighborsRegressor,Ridge,GradientBoostingRegressor)

etudes des learning curve et choix de meilleure modele(LinearRegression)

optimisation de modele(GridSearchCV)

modele final a l'aide d'ensemble methode(StackingRegressor)

# house_price_predict_amsterdam

pour la deuxieme application concerne la ville de lille c'est un programme basique dans le but de voir l'aspet mathematique derierre la regresion lineaire 
programme est divisee en 4 fonction:

Prediction_PLille : pour la prediction

regression_alge: programmation de l'aspet mathematique de la regression multiple 

comparaison_Plille : comparaison de prediction base sur sklearn  

main : fonction principal du programme ( preprocessing  , la regression lineaire a l'aide du modele predifinie de sklearn et la fonction regression_alge)


