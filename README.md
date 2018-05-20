# Application de calcul de taxes

## Domaine

Pour modéliser le besoin de l'énoncé les classes ci-dessous ont été créées.

### `Product`
`Product` représente un produit. 
Un produit a les caractéristiques suivantes :
 - **name** : nom du produit
 - **type** : type du produit. La liste des types possibles est définie dans l'énumation Type. Ces valeurs sont : BOOK (pour les livres), FOOD (pour la nourriture), MEDICAL (pour les médicaments) et OTHER (pour tout autre produit).
 - **quantity** : la quantity des produits
 - **price** : prix d'un produit
 - **imported** : indique si le produit est importé ou pas

### `ShoppingBag`
Un panier d'achat contenant la liste des produits.
 - **products** : liste des produits qui composent le panier d'achat
 
### `Purchase`
Purchase représente un achat. 
Un achat a les caractéristiques suivantes :
- **product** : le produit acheté
- **taxAmount** : le montant des taxes appliquées pour l'achat du produit
- **totalAmount** : montant du prix d'achat (taxes comprises) 

### `Receipt`
Receipt représente un ticket de caisse. 
Il liste les achats effectués, le montant total des taxes et le montant total de la facture.
 - **purchases** : liste des achats
 - **taxAmout** : montant total des taxes pour tous les achats
 - **totalAmount** : montant total des achats (taxes incluses)

## Choix de définition du domaine 
La taxe ne fait pas partie du produit, car celle-ci peut changer et n'est donc pas une propriété définissant un produit.

La classe `Purchase` permet de modéliser le calcul des taxes sur les produits. Elle permet aussi de calculer le prix total en prenant en compte les taxes appliquées.

## Calcul des taxes

### Principe

### Choix


## Formattage des montants

## Axes d'amélioration

## Conclusion

