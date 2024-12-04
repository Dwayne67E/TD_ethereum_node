# TD Ethereum Node  
*Monnaie numérique - Course*

## Choix des types de clients

L'architecture d'un nœud Ethereum se compose de deux types de clients :  
1. **Client d'exécution** :  
   - Traite les transactions et maintient l’état de la blockchain.  
   - Gère l'interaction avec les smart contracts.

2. **Client de consensus** :  
   - Assure la validation des blocs.  
   - Maintient le consensus au sein du réseau.

### Importance de la diversité des configurations

Pour sécuriser le réseau Ethereum, il est essentiel que les configurations des nœuds soient diversifiées. Cela permet de réduire les risques liés à la centralisation ou à une éventuelle vulnérabilité affectant une implémentation spécifique.

### Choix des clients

Afin de favoriser cette diversité, nous optons pour les implémentations suivantes :  
- **Besu** : Client d'exécution écrit en Java, conçu pour une compatibilité étendue et souvent utilisé dans des contextes d'entreprise.  
- **Nimbus** : Client de consensus écrit en Nim, léger et adapté aux systèmes à faible consommation de ressources.  

Ces deux clients sont minoritaires dans le réseau Ethereum, ce qui contribue à renforcer la résilience et la robustesse du réseau global.
![image](https://github.com/user-attachments/assets/8dd488ae-8357-4e27-bbb2-e08566f2b2ec)
