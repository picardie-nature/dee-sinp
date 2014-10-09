##Utilisation des fichiers d'échanges du SINP

Pour obtenir le standard en vigueur et la documentation rendez-vous sur la page du [groupe de travail SINP sur le standard de données](http://www.naturefrance.fr/actions/groupe-de-travail-standardisation-des-donnees-biodiversite-du-sinp) 

##Mémento des commandes pour valider un document xml

Pour tester si un export est valide

```
xmlstarlet val -s Collection.xsd export.gml

```

ou

```
xmllint --schema Collection.xsd export.xml
```



Pour indenter un fichier xml

```
xmlstarlet fo doc.xml > doc_indente.xml
```
