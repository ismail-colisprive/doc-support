## Réponse des Web Services
Pour récupérer les réponse du Ws Services, ouvrez la console JavaScript de votre navigateur, puis rendez-vous sur l'onglet "Réseau | Network"

![Figure 04 - Ouverture de l'onglet Network](../img/onglet-network.gif)

Vous pouvez cochez l'option **Preserve log** afin de garder les requêtes envoyées même si vous actualisez la page 
Vous pouvez filtrer les requêtes en choisssisant le filtre **Hetch/XHR** pour voir que les requêtes qui font appelent à des Web Services
![Figure 05 - Filtre ](../img/filtre-request.png)

![Figure 06 - Onglet réseau de la console ](../img/tableau-console.png)
le tableau ci-dessous décrit les partie importantes de la figure 06

| Name | Status | Type | Initiator | 
| ----------- | ----------- | ----------- | ----------- |
| Nom de la requête | Statut de la réponse | Son type | Le fichier déclencheur |

Séléctionner la requête que vous souhaitez consulter en choisissant cette dernière dans la partie **Name**

![Figure 07 - ](../img/request.png)

La figure **08** représente la requête, dans le premier onglet on trouve l'entête de la request **Header**
Dans l'onglet **Payload** on aura le corps de la requête **Body** 
Les onglets **Preview** et **Response** on aura la réponse du serveur
![Figure 08 - ](../img/Request-sended.png)