# Titles

Comme nous avons commencé à écrire un document, nous devons rajouter un titra et quelques sous-entête.

Markdow prend en charge deux styles d’en-têtes, Setext et atx.

Les en-têtes de type Setext sont « soulignés » en utilisant l’égalité et de tirets (pour les sous en-têtes). Exemple : 

```
This is an H1
=============

This is an H2
-------------
```

N’importe quelle nombre entre les lignes =’s ou -’s marchera.

Les en-têtes  le style Atx utilise 1.6 caractère pour commencer une ligne .

```
# This is an H1

## This is an H2

###### This is an H6
```


En option, on peut « fermer » les en-têtes avec le style atx. Vous pouvez utiliser ceci si vous penez qu’il semble mieux. Les hash de fermeture n’ont pas de correspondre au monbre de hash utilisé ouvrir ouvrir l’en-tête.

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Les en-têtes ont besoin d’espace entre les caractères de hash et le texte.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


