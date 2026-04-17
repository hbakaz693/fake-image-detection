
# Fake Image Detection Project:Construction au model IA a zero
Ce projet vise à détecter les images générées par IA et les distinguer des images réelles en utilisant le Deep Learning.
## Objectifs
- Détecter les images fake vs real
- Construire un modèle CNN
- Évaluer les performances

## Structure du projet
fake-image-project/
├── datasets/
├── code/
└── results/

## Étapes detailles  du projet
### 1. Création des dossiers sur drive

dossier fake-image-project:dossier global de peoject
dossier datasets:contient datastes utilise 
dossier results:pour stocker les resultats 

### 2. Téléchargement de datasets depuis Kaggle
<img width="506" height="118" alt="image" src="https://github.com/user-attachments/assets/7f318f50-f648-47f2-a08f-16d7a2d03fc1" />


Remarque: 
Le commande pour telecharger datasets dans le drive est : <img width="380" height="19" alt="image" src="https://github.com/user-attachments/assets/91790a0d-607a-403c-b423-d2225d016d18" />


creature/nom-datasets
Ceci ce fait apres la configuration de Kaggle sur Colab 


## 4. sauvgarder et Unzip datasets dans le dossier datasets dans le drive 
Apres la connexion Avec Drive(Colab connecter avec Drive)


<img width="554" height="22" alt="image" src="https://github.com/user-attachments/assets/bef22cee-24d9-4a66-96a6-9f5431eb7c65" />


## 5. Prétraitement
✅ 1ère étape du prétraitement : charger et lire les images ou verifier que la datasets est bien Organiser


<img width="293" height="83" alt="image" src="https://github.com/user-attachments/assets/51ec2d0a-fe99-45b5-9ad4-24af8826a5b9" />



✅ 2ère étape du prétraitement : resize des images et Normalisation 
    Objectif : Les CNN besone des images de meme taille 
               Le plus utilise (224x224)
               Normalisation : mettre les pixels entre 0 est 1 au lieu de 0-255 pour accelerer l'apprentissage



<img width="332" height="135" alt="image" src="https://github.com/user-attachments/assets/4e8d5eab-6545-432c-b99e-fc25e7e14f64" />




## 6 . Creation de  Label X et y 


<img width="184" height="22" alt="image" src="https://github.com/user-attachments/assets/2c13cb22-de57-4ba7-9de2-d0364953c7fa" />


## 7 . Separer les donner en train et test 


<img width="370" height="145" alt="image" src="https://github.com/user-attachments/assets/215d52fe-cca3-4774-a72d-bf4fbbaf47e6" />



# 8 . Construire le Modele 
c'est l'etape le plus imporatnt de construction de notre projet 
dans cette Etpa on va utiliser CNN 
On va diviser cette etape au plusier etape pour le comprend bien :


🧠 📌 Étape 1 : Architecture du modèle CNN
CNN : Est deja comme une reseaux des neurones qui permet la creation des model qui traiter les image 
Ce code montre tous les etape de construction de model A a Z(les etapes en detailles)













               



















