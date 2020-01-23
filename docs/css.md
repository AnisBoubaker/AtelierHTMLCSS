# Les feuilles de style CSS

## Introduction

Le CSS (*Cascading Style Sheets*) est un langage permettant de définir l'apparence d'un document de la famille XML (XML, HTML, MathML, SVG, etc.) en spécifiant un ensemble de règles de formatage des éléments du document. Les règles de formatage permettent de spécifier tout ce qui concerne l'apparence d'un document décrivant comment ce dernier devrait apparaitre à l'écran, sur papier, à la lecture, etc. Les règles vont de la spécification de la couleur ou de la fonte des textes, jusqu'aux règles de placement des différents éléments à l'écran.

Selon la logique de séparation du contenu et du visuel, nous avons défini le contenu du document dans un fichier HTML. Nous définissons maintenant un fichier CSS où l'on définit son apparence visuelle. 

Il est toutefois possible de spécifier l'apparence d'un élément directement dans une balise, à travers l'attribut `style`. Par exemple, le paragraphe ci-dessous verra son texte écrit en rouge: 

```html
<p style="color: #ff0000">
  Ce texte sera écrit en rouge.
</p>
```

Cependant, inclure les règles de style directement dans une balise contredit le principe de séparation entre le contenu et le visuel. Nous préférons ainsi isoler les règles de formatage dans un document CSS. Un document CSS est un fichier texte dans l'arborescence du site ayant typiquement l'extension `.css`. 

## Les sélecteurs CSS

Un sélecteur est une chaine de caractère permettant de cibler un ou des élements de l'arborescence du document HTML. Il existe plusieurs types de sélecteur afin de cibler par exemple: 

- Tous les éléments d'un type spécifique (ex.: tous les `<p>`) 
- Le éléments ayant une classe particulières (`<... class="une_classe">...`) ou un identifiant particulier (`<... id="un_identifiant"... >`)
- Tous les éléments descendants d'un élément particulier
- Tous les éléments ayant une valeur particulière pour l'un de ces attributs. 
- etc.

Le sélecteur est utile pour spécifier des règles de formattage spécifiques pour un ou des éléments du document. 

Suivez ce lien pour découvrir la [liste exhaustive des sélecteur CSS](https://www.w3schools.com/cssref/css_selectors.asp) sur le site de W3School. 

