# BLOCKCHAIN_AND_DEEP_LEARNING

![image](https://user-images.githubusercontent.com/94251665/212698846-e803f84d-408f-40d3-905e-e980e4dea616.png)

Le Blockchain est un système de stockage et de transmission d'informations, organisé sous forme de blocs reliés entre eux par des liens cryptographiques. Il permet de stocker des informations de manière décentralisée, ce qui signifie qu'il n'y a pas de tiers de confiance ou d'autorité centrale qui gère les données. Les données sont stockées sur plusieurs ordinateurs, appelés nœuds, qui font partie du réseau.

![image](https://user-images.githubusercontent.com/94251665/212698881-9b6643c3-4349-4d02-98e1-bdd6cf63f5fe.png)

La crypto-monnaie est une forme de monnaie numérique qui utilise la technologie de la cryptographie pour sécuriser les transactions et pour contrôler la création de nouvelles unités.

Dans ce projet on a 2 phases :

La 1er :
Analyse des investissements en crypto-monnaie
voici quelques resultats

![image](https://user-images.githubusercontent.com/94251665/212699569-20e724df-16f9-4915-a9bc-f259616e284b.png)

![image](https://user-images.githubusercontent.com/94251665/212699702-43de5aa4-43b3-4f77-a37f-5d1d240fcfa1.png)

![image](https://user-images.githubusercontent.com/94251665/212699756-d4e52080-3341-43d5-bd27-79f9a3a3e2f3.png)

La 2eme :
Prédire les prix des crypto-monnaies : bitcoin

Ici j'ai creer une nouvelle architecture pour la prediction du prix du bitcoin

-un RNN à 3 couches avec un dropout de 20% à chaque couche 

-Ce modèle aura 515 579 paramètres entraînables dans toutes ses couches.

-l'AdamOptimizer comme fonction d'optimisation!

-La fonction de perte utilisée dans ce modèle est l'erreur quadratique moyenne.

-La fonction d'activation linéaire est simplement définie comme f(x) = x.

-Le modèle utilisera le modèle séquentiel de Keras avec des couches LSTM bidirectionnelles.

voici quelques resultats

![image](https://user-images.githubusercontent.com/94251665/212700618-90d2094f-6199-4272-baa2-e3fe6e2dee3f.png)

![image](https://user-images.githubusercontent.com/94251665/212700652-a6c62694-ff09-49f8-87f0-9e6e102e1aec.png)


Precision : 0.72


