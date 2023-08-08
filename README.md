# OCR5
## OpenClassRooms projet 5: Classifiez automatiquement des biens de consommation

### Données

### Mission  
  1. Réaliser, dans une première itération, une étude de faisabilité d'un moteur de classification d'articles, basé sur une image et une description, pour l'automatisation de l'attribution de la catégorie de l'article.
  2. Une réduction en 2 dimensions
     ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/bdae7742-7018-4bd4-873c-03aac60505bd)
  3. Analyse du graphique afin d’en déduire faisabilité de regrouper automatiquement des produits de même catégorie.
  4. Réalisation d’une mesure pour confirmer ton analyse visuelle.
  5. Prétraitement et analyse textuelles et images (**SIFT / ORB / SURF, CNN Transfer Learning**) des produits.
      - **Prétraitement textuelles**
     ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/7e6f27c7-dbe6-4cf7-915c-8c35833b0e7a)
      - **Analyses textuelles: Bag-of-words, Tf-idf, Word2Vec, BERT, Universal Sentence Encoder**
     ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/bd38db78-99ab-47d5-8291-829f7306ff50)
     ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/e3529745-45e7-4596-affa-33e8a6ec60d3)
     ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/86246950-b080-49cf-a4d7-be3f98e0f57a)
      - **Prétraitement images**
        ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/625a01d5-c69a-4b75-8243-9c7dd387dd8a)
      - **Analyses images: Extraction des prédicteurs, Kmean sur prédicteurs, Bag of Visual words**
        ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/b2df1310-7420-43e4-b3bb-7df6818f789d)
      - **Analyses images: Transfert learning ImageNet VGG16 entraînement non supervisé**
         ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/2970d66d-0b30-4523-8ebe-5f81bf169d2c)
        ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/a5d53c77-b115-4e09-8871-e2ca8e7c80e5)
      - **Analyses images: Transfert learning ImageNet VGG16 entraînement supervisé**
        ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/38a42177-58cc-44b0-b860-35d49b0c346e)
        ![image](https://github.com/SebastianSosa/OCR5/assets/22368172/43c99953-9ba4-4503-8e49-b321a898683d)
    

### Compétences évaluées
  1. Prétraiter des données image pour obtenir un jeu de données exploitable
  2. Prétraiter des données texte pour obtenir un jeu de données exploitable
  3. Représenter graphiquement des données à grandes dimensions
  4. Mettre en œuvre des techniques de réduction de dimension
  5. Utiliser des techniques d’augmentation des données
  6. Définir la stratégie de collecte de données en recensant les API disponibles
  7. Définir la stratégie d’élaboration d’un modèle d'apprentissage profond
  8. Évaluer la performance des modèles d’apprentissage profond selon différents critères

### Livrables 
  1. Un ou des notebooks contenant les fonctions permettant le prétraitement et la feature extraction des données textes et images ainsi que les résultats de l’étude de faisabilité (graphiques, mesure de similarité).
  2. Un notebook de classification supervisée des images.
  3. Un script Python de test de l’API et le fichier au format “csv” contenant les produits extraits.
  4. Un support de présentation pour la soutenance, détaillant le travail réalisé.
