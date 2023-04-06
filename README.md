# Projet de réponse automatique sur Twitter
Ce projet utilise l'API Twitter et la bibliothèque Python Tweepy pour répondre automatiquement aux tweets qui contiennent certains mots-clés. 

L'objectif est de répondre à des utilisateurs Twitter qui cherchent des informations sur des villes américaines en leur fournissant des données spécifiques.

# Prérequis
* Un compte Twitter et des clés d'API Twitter Developer pour accéder à l'API Twitter
* Python 3.x avec les bibliothèques Tweepy et time installées

# Utilisation
* Clonez ou téléchargez le repository sur votre ordinateur.
* Créez un fichier "reply.txt" contenant la réponse que vous souhaitez envoyer aux utilisateurs Twitter.
* Créez un fichier "Cities.txt" contenant une liste des villes américaines que vous souhaitez cibler.
* Créez un fichier "keywords.txt" contenant le mot-clé que vous souhaitez surveiller.
* Exécutez le script Python "twitter_bot.py".
Le programme recherche régulièrement les tweets contenant le mot-clé spécifié et vérifie si l'utilisateur est situé dans l'une des villes cibles. Si ces conditions sont remplies, le bot envoie une réponse prédéfinie à l'utilisateur.

# Limitations
Le bot est limité par le taux de requêtes autorisées par l'API Twitter. Si vous dépassez ce quota, vous risquez d'être temporairement bloqué par l'API Twitter.

De plus, le bot peut être trompé si un utilisateur Twitter modifie intentionnellement son emplacement ou s'il utilise des termes similaires au mot-clé spécifié.

# Contributions
Les contributions à ce projet sont les bienvenues. Si vous avez des idées d'améliorations ou des corrections à apporter, n'hésitez pas à ouvrir une pull request ou une issue.

# Licence
Ce projet est sous licence MIT. Consultez le fichier "LICENSE" pour plus d'informations.

# Auteur 
Le projet a été créé par Lefranc Nicolas en 2021.