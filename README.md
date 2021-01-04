# SPARK-ML-

Objectif:prédire les clients qui vont résilier leur abonnement chez un opérateur téléphonique

Prerequisites

    Apache Spark 2.2.
    Python 3.6.
    PySpark2PMML 1.3.15
    
    
 Launch
 
    Lancer le code pyhton sur colaboratory. 
    
    Contenu: dataset, data visualisation, model de prédiction 
    
 Problèmatique:
 Lorsqu'on veut exporter le résultat sous format PySpark2PMML, on obtient cette erreur: "RuntimeError: JPMML-SparkML not found on classpath". 
 
 Bien que j'ai changé les versions car je pensais qu'il y avait une incompatibité, rien n'y fais. L'objectif était d'exporter le résultat sous ce format afin de pourvoir l'expoiter en frontend JS. 
