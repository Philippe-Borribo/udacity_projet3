# Exploration du système Ford GoBike

Auteur : Philippe BORRIBO

## Dataset

Dans le cadre du projet 3 du nanodegree Udacity Data Analysis, nous ferons une analyse exploratoire des données du dataset '201902-fordgobike-tripdata.csv'. Celui-ci contient les informations sur les trajets individuels effectués dans un système de partage de vélos couvrant la grande région de la baie de San Francisco.

Le dataset est disponible [Ici](https://github.com/Philippe-Borribo/udacity_projet3.git)

## Resumé des observations

Dans notre étude, nous avons voulu déterminer l'impact que certianes variables
auraient sur la durée d'un parcours à vélo. Celà nous a amené ressortir les 
distributions telles que la distribution de la durée, des participants et des 
ces derniers en fonctions de plusieurs autres variables telles que l'année de 
naissance, le genre et le type dans le but de prédire si l'une d'entre elles a
une incidence directe sur la durée du parcours. Le résultat a plutôt été 
satisfaisant. 

Après les distributions, nous nous sommes attaqués à l'analyse bivariée pour 
voir les différentes corrélations entre les variables de notre dataset et notre
variable phare. Plusieurs correspondances ont été faites et ont permis de 
déterminer les variables susceptibles d'impacter de manière significative la 
durée du parcours.

Pour finir, nous sommes allées encore un peu plus loin avec, cette fois-ci, 
l'analyse multivariée pour voir l'effet d'une variable x sur la durée lorsqu'elle
est combinée à une variable y. Et là aussi les résultats sont assez étonnants.

## La présentation

En ce qui concerne la visualisation, nous avons mis l'accent les variables : 'user_type',
'member_gender' et 'member_birth_year' dans le but d'ibserver l'impact de l'âge, du
genre et du type (abonné ou client) sur la durée du parcours.

Nous avons commencé premièrement par les corrélations pour voir les l'impact avec les
variables numériques. Ensuite, nous sommes passés aux variables catégorielles parmi
lesquelles se trouvent nos 3 variables d'intérêts.




















