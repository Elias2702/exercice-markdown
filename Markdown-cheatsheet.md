
# MARKDOWN un langage rapide et facile à lire.


>Le Markdown est un langage de balisage inventé par **John Gruber** en 2004 permettant de formater du texte brut de manière simple >pour un rendu en HTML ou dans un autre format. [Guillaume BELFIORE](https://www.futura-sciences.com/tech/definitions/informatique-markdown-17135/).

#Markdown Cheatsheet
## Qu'est-ce que Markdown ?
Selon Wikipedia :
> Markdown est un langage de balisage léger créé en 2004 par John Gruber avec Aaron Swartz1,2. Son but est d'offrir une syntaxe facile à lire et à écrire. Un document balisé par Markdown peut être lu en l'état sans donner l’impression d'avoir été balisé ou formaté par des instructions particulières.
Un document balisé par Markdown peut être converti en HTML ou en autres formats. Bien que la syntaxe Markdown ait été influencée par plusieurs filtres de conversion de texte existants vers HTML — dont Setext3, atx4, Textile, reStructuredText, Grutatext5 et EtText6 —, la source d’inspiration principale est le format du courrier électronique en mode texte.

![Le logo de Markdown](http://kirkstrobeck.github.io/whatismarkdown.com/img/markdown.png)
___
## Syntaxe
### Les titres
Pour réaliser des titre on précède le texte visé de dièse (#) comme suit:

    # Le Titre souhaité

On peut changer l'importance d'un titre en ajoutant des dièses. Ainsi 1 '#' fera 1 h1, 2 fera 1 h2 etc...

### Les paragraphes
Pour faire différents paragraphes il suffit de laisser au moins un ligne vide entre 2 autre comme suit:

    ``` markdown
    Un premier paragraphe
    <!-- Une ligne vide -->
    Un second paragraphe
    ```

### Mise en gras
Pour mettre en gras du text il suffit de l'entourer par 2 astérisques (**) comme suit:

    **le texte à mettre en gras**

### Mise en italique
Pour mettre du texte en italique, on l'entoure d'un underscore (_) comme suit:

    _Texte en italique_

### Création d'un tableau
Il faut séparer les colonnes par des traits verticaux (|) et des deux-points :

```
  | Tables        | Are           | Cool  |
  | ------------- |:-------------:| -----:|
  |     cell      | cell          | cell  |
  |     cell      | cell          | cell  |
  |     cell      | cell          | cell  |
```

### Insertion de code
Il faut entourer les lignes de codes avec 3 accents graves (`)
**Ne pas mettre les parenthèses !**
```
  (```)
  chaine = "Becode Power"
  for lettre in chaine:
    print(lettre)
  (```)
```

### note de bas de page
Syntaxe avec les crochets et l'accent circonflexe.
```
  Voir la note en bas de page. [^1]
  [^1]: Note de bas de page.
```

### créer un ID (dans ce cas sur un heading)
Syntaxe avec {} et #
```
### My Great Heading {#custom-id}
```

### texte barré
Avec le signe ~
```
~~La terre est plate.~~
```
