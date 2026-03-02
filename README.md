# Classification_Sequence_TransferLearning

Le but de ce projet est de classifier des émails reçus par une grande entreprise bancaire et ainsi trier ces-derniers dans les départements correspondant aux objets des requêtes faîtes par les clients, collaborateur etc.
Ainsi, nous avons utilisé un réseau de neuronne pré-entraîné (BART) sur des millions de textes en français et possédant déjà plusieurs millions de paramètres. Nous aurons donc qu'à **fine-tuned** les dernières couches de notre modèle finale afin que ce-dernier soit un expert dans la classification d'émails.



https://github.com/eygann/Classification_Sequence_TransferLearning/blob/main/Sequence_classification.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]

Bien que le jeu de données d'entraînement et le jeu de test sont incomplets et ne représentent que trop peu de données pour garantir un fonctionnement performant et robuste de notre modèle en condition réelle dans l'industrie. Ce projet montre particulièrement bien **ET** l'utilisation - l'application du transfer learning **ET** l'expertise du modèle dans la classification par rapport aux peu de données à disposition pour l'entraînement ce qui peut s'avérer être un atout majeur dans des domaines dans lesquels les données sont rares et/ou chers à collecter et traiter.
