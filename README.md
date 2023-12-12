# Le Web Service SOAP

Dans ce fichier Lisez-moi, je fournirai un rapport sur les éléments suivants :

1. La création d'un service web.
2. Le déploiement du service web.
3. La consultation et l'analyse du WSDL dans un navigateur HTTP.
4. Le test du service web à l'aide de SoapUI.
5. La création d'un client SOAP qui consomme le service web.

## La création du service Web

Dans cette partie, j'ai créé une simple classe Java nommée "BanqueService". J'ai ensuite utilisé les annotations appropriées pour le transformer en service web,
comme le montre l'image ci-dessous :

![1](https://github.com/Yahyaa55/JEE_Activity_one/assets/100850367/7bdc6828-a25c-456a-aa2b-c810fd9c8c04)

## Le déploiement du service Web

Pour déployer le service Web, j'ai créé une classe nommée "ServerJWS". À l'intérieur, j'ai créé une méthode principale pour publier notre service Web, 
le rendant accessible via n'importe quel appareil connecté localement via l'adresse http://0.0.0.0:9191, comme le montre l'image ci-dessous :

![2](https://github.com/Yahyaa55/JEE_Activity_one/assets/100850367/4a5b7d24-db30-4702-91c9-c19c6ee03706)

## La consultation et l'analyse du WSDL dans un navigateur HTTP

Maintenant que le web service est publié, je peux consulter le WSDL via le navigateur en utilisant l'adresse http://localhost:9191/?WSDL, comme le montre l'image ci-dessous :

![3](https://github.com/Yahyaa55/JEE_Activity_one/assets/100850367/7c7733b2-d553-4f63-b30c-46e85dc7eb0d)

## Le test du service Web à l'aide de SoapUI

Pour tester les méthodes du service Web publié, j'ai utilisé SoapUI comme outil de test. Dans l'image ci-dessous, 
j'ai exécuté deux tests, un avant d'ajouter l'annotation @Transient au champ date de la classe de compte :

![4](https://github.com/Yahyaa55/JEE_Activity_one/assets/100850367/2207ae7b-e170-49c0-8057-beefdf9bf9ad)

## La création d'un client SOAP qui consomme le service Web

Enfin, pour consommer le service web, j'ai créé un client Java qui utilisera les méthodes du service web, comme le montre l'image ci-dessous :

![5](https://github.com/Yahyaa55/JEE_Activity_one/assets/100850367/02c342ba-f774-41c3-91b6-d79c48dd14c8)
