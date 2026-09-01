# Flight Delay Prediction

## Dataset

Pour ce projet j'ai manipulé un dataset sur des vols aériens américains récupéré sur Kaggle (`Airlines.csv`), avec environ 540 000 vols (compagnie, aéroport de départ/arrivée, jour, heure, durée, et si le vol a été en retard). voici le lien du dataset : https://www.kaggle.com/code/sonialikhan/airlines-dataset-to-predict-a-delay/input

## Ce que j'ai fait

Dans ce projet j'ai voulu comprendre puis prédire les retards de vols. Pour cela j'ai commencé par explorer le dataset (nombre de vols, jours les plus chargés, taux de retard global) pour bien comprendre les données avant de commencer.

Ensuite j'ai trié les vols en retard pour les comparer aux vols à l'heure, regardé quelles routes étaient les plus touchées, et cherché des corrélations entre les variables et le retard.

Pour finir je suis passé à l'encodage des colonnes texte (compagnie, aéroports) avec `LabelEncoder`, puis j'ai testé deux modèles de machine learning (Régression Logistique et Random Forest) pour prédire si un vol sera en retard, et comparé leurs résultats avec l'accuracy et la matrice de confusion.

## Technos utilisées

Pour ce projet j'ai utilisé Python avec les librairies Pandas, Matplotlib et scikit-learn, et DataSpell comme environnement de développement.
