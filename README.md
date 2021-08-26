# exo-alo-coulibaly-yaya

ecrire un algoritme permettant de :
verifier l'egalite numerique ente deux nombres donnée
calculer le taux de contammination de la CI
cas : 85
deces : 2
nombre de cas: 187
montrer qu'une année donnée est non bissextile

---

## Exo 1

Calculer le taux de contamination de la côte d'ivoire
nombres de cas : 85
nombre de personne teste : 187

1. Algorithme : **tauxDeContamination**;

2. VAR nbPersInfecte, nbPersTeste, taux: Reel;

3. **Debut**

Afficher("entre le nombre de personne teste");
Saissir(nbPersTeste);

Afficher("enter le nombre de cas positif");
Saissir(nbPersInfecte);

...
taux = ( nbPersInfecte * 100 ) / nbPersTeste;
...
Afficher("le taux de contamination de la cote d'ivoire est :",taux);
**Fin**

---

## Exo 2

Montrer qu'une année est bissextile

1. Algorithme : **anneeNonBissextile**;

2. VAR anne, resultat: Reel;

3. Debut

Afficher("saisissez une année");
Saissir(anne);
if( ((anne MOD 4 == 0) AND (anne MOD 100 <> 0)) OR (anne MOD 400 == 0)) alors
    Afficher("l'année ", anne, " est une année bissextile");
sinom
    Afficher("l'année ", anne, " est pas une année bissextile");
finsi
**fin**
