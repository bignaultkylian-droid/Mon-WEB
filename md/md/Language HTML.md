


**Ex**

Il existe aussi des balises orphelines : `<!DOCTYPE html, <br>, <img> ...`

Référence: Mozilla [https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements)

Une balise ouvrante peut contenir un attribut notamment `class=""`:

`<html class="maClasse"></html>`

Quelques balises importantes:
- `<h1></h1>`: pour faire des titres
- `<p></p>`: pour faire des paragraphes
- `<a href=""></a>`: pour faire des liens
- `<ul></ul>`:pour faire des liste sans ordre
- `<ol></ol>`: pour faire des listes avec ordre
- `<li></li>`: pour faire des items de liste
- `<img src="">`: pour ajouter une image

Pour trouver le chemin vers un fichier, on peut regarder:
- dans le dossier courant avec `./`
- dans un dossier extérieur avec `../`

2. CSS

Cascading Style Sheet : page de style en cascade

On peut écrire du CSS:
- directement dans le fichier HTML entre les balises `<style></style>`
- Dans un fichier `.css` en indiquant le chemin dans le fichier HTML grâce à la balise `<link>`

Pour écrire du CSS, il faut un sélécteur (nom d'une balise ou d'un class), des accolades, des propriétés, des valeurs.

```css
selecteur{
    propriete1 : valeur 1;
    propriete2 : valeur 2;
    ....
}

Il existe plus de 500 propriétés et encore d'avantage de valeurs possibles. Cependant, les valeurs sont souvent:
- une couleur: un nom, un code (RGB(0-255,0-255,0-255))
- une taille: il existe de nombreuses unités , pixels(px), pourcentage(%)

Rem: on trouve toute les propriétés sur le site des developpeurs de Mozilla.

Les propriétées CSS s'appliquent en cascade : des éléments les plus globaux (`body`, `div`) vers les éléments les plus internes (pour finir par les classes).

Rem: Principe du modèle en boîte
Les éléments d'une page sont contenus dans une boîte entourée d'une bordure(invisible par défaut).
L'espace entre:
- le contenu et la bordure s'appelle `padding`
- la bordure et éléments autour s'appelle `margin`

La bordure `border` peut même avoir un style.
[https://www.w3schools.com/Css/css_boxmodel.asp]
(https://www.w3schools.com/Css/css_boxmodel.asp)

Ils existe de nombreuses propriétés 


3) JavaScript (JS)

C'est le language de programmation qui permet de gérer les éléments interactifs d'une page HTML.

Historiquement, les éléments d'interactions étaient placés dans un formulaire `<form></form>` pour renvoyer des informations au serveur.

Dans le formulaire on place les éléments `<input type="">`:
- type="text"
- type="checkbox"
- type="bottom"

rem: Une balise `<button type="button"></button>` a été spécifiquement créée pour les boutons

On peut le JS directement:
- dans le fichier HTML entre des balises `<script></script>`
- dans un fichier externe avce l'extension .js

On utilise la balise script pour lier le fichier js.

JS est utilisé pour réagir aux évènements : `click`, `change`, `mouseover`, ...

La syntaxe basique est:

```js
elementHTML.addEventListener('event' , function(){......})

```