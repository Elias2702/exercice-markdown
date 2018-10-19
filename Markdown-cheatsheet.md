
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

### Liens & Images

```
[Texte du lien](http://url.com/ "Title")

-----------------------------------

![Texte image](http://www.example.com/files/sample.png)
```

### Liste à puce

Pour créé une liste à puce, il suffit d'ajouter un astérisque en début de ligne.
```
* Example 1
* Example 2
* Example 3
```

* Example 1
* Example 2
* Example 3

Vous pouvez également créé des sous-puces de cette manière.

```
* Example 1
* Example 2
      * Example 2.1
      * Example 2.2
* Example 3
```
* Example 1
* Example 2
    * Example 2.1
    * Example 2.2
* Example 3

Vous pouvez également appliquer des listes numérotées, pour cela, rien de plus simple :

```
1. Numéro 1
2. Numéro 2
3. Numéro 3
```
1. Numéro 1
2. Numéro 2
3. Numéro 3

### Citations

Si vous souhaitez appliquer une citation, vous devrez procéder comme ceci :

```
> Citation d'un grand philosophe alcoolique
> Citation d'un autre grand philosophe (mais sobre cette fois)
```

> Citation d'un grand philosophe alcoolique

> Citation d'un autre grand philosophe (mais sobre cette fois)
