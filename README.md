# MachineLearningProject
J'ai suivi le tutoriel du site "https://towardsdatascience.com/how-to-easily-deploy-machine-learning-models-using-flask-b95af8fe34d4", écrit par Abhinav Sagar.
Dans cette application, on a crée un modèle de machine learning et on l'a déployé avec flask. L'auteur a utilisé la régreession linéaire pour prédir la valeur des ventes au cours du troisième mois en utilisant le taux d'intérêt et les ventes des deux premiers mois.
Le projet et divisé en 4 parties :  
  - model.py : code pour le modèle de machine learning qui fait les prédictions des ventes du troisième mois
  - app.py : contiens les api flask qui reçcoivent les détails des ventes via des appels GUI oui API, calcul la valeur en fonction du modèle crée, et la renvoie.
  - request.py : utilise les modules request pour appeler les API de app.py et affiche la valeur envoyée.
  - HTML / CSS - Il contient le modèle HTML et le style CSS pour permettre à l'utilisateur de saisir les détails des ventes et d'afficher les ventes prévues au troisième mois.
