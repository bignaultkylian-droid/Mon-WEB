


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
- Dans un fichier `.css`

Pour écrire du CSS, il faut un sélécteur (nom d'une balise ou d'un class), des accolades, des propriétés, des valeurs.

```css
selecteur{
    propriete1 : valeur 1;
    propriete2 : valeur 2;
    ....
}
