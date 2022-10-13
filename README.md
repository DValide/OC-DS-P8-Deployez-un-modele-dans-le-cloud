![image](https://user-images.githubusercontent.com/25401003/191027081-d4f528b2-9c71-491f-8749-d18cb3b999fe.png)

## Enoncé 
Vous êtes donc chargé de **développer** dans un environnement **Big Data** une première chaîne de traitement
des données qui comprendra le **preprocessing** et une étape de **réduction de dimension**.

Il n’est *pas nécessaire d’entraîner un modèle* pour le moment.

L’important est de **mettre en place les premières briques de traitement** qui serviront lorsqu’il faudra passer à l’échelle en termes de volume de données !

### Contraintes
Lors de son brief initial, Paul vous a averti des points suivants :

Vous devrez tenir compte dans vos développements du fait que le volume de données va augmenter très rapidement après la livraison de ce projet. Vous développerez donc des scripts en Pyspark et utiliserez par exemple le cloud AWS pour profiter d’une architecture Big Data (EC2, S3, IAM), basée sur un serveur EC2 Linux. La mise en œuvre d’une architecture Big Data sous (par exemple) AWS peut nécessiter une configuration serveur plus puissante que celle proposée gratuitement (EC2 = t2.micro, 1 Go RAM, 8 Go disque serveur).

## Livrables attendus

 * Un notebook sur le cloud contenant les scripts en Pyspark exécutables (le preprocessing et une étape de réduction de dimension).
 * Les images du jeu de données initial ainsi que la sortie de la réduction de dimension (une matrice écrite sur un fichier CSV ou autre) 
      disponible dans un espace de stockage sur le cloud.
 * Un support de présentation pour la soutenance, présentant :
    - les différentes briques d'architecture choisies sur le cloud ;
    - leur rôle dans l’architecture Big Data ;
    - les étapes de la chaîne de traitement.
