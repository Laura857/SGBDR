# SGBDR

> Projet annuel L3
>
> 3 développeurs :  Laura TRICHET - Nelly UNG - Chirel COHEN

SGBDR est un projet annuel qui avait pour objectif de créer un mini SGBDR (Système de Gestion d’une BDD Relationnelle) 
simplifié en Java, avec un seul utilisateur et une unique base de données.

Ce projet contient les fonctionnalités suivantes :
- Gestion disque
- Création de table
- Insertion
- Sélection
- Jointure avec "page oriented nested loop".


# Commandes possible depuis le terminal pour SGBDR
Pour créer : create nomRel nbrCol typeCol1, typeCol2 ... typeColn
Pour insérer un élement : insert nomRelation val1 val2 ... valn
Pour insérer plusieurs élements : insertall nomRel fichier.csv
Pour séléctionner tous les records d'une relation: select nomRelation indiceColonne valeur
Pour séléctionner certains records d'une relation : selectall nomRelation
Pour supprimer un Record : deleteate nomRel indiceColonne valeur
Pour créer un index : createindex nomRelation indice_colonne ordre
Pour séléctionner un index : selectindex nomRelation indiceColonne valeur
Pour faire une jointure : join nomRel1 nomRel2 indiceColonne1 indiceColonne2
Pour tout nettoyer : clean
