# HTML
À quoi servent les balises \<!doctype html\>, \<html\>, \<head\>, \<title\> et \<body\>.

## 1. \<!doctype html\>
Tout fichier HTML doit commencer par la balise \<!doctype html\>. <br>
Cela permet au navigateur de connaître le type de fichier qu'il va lire et donc garantir la meilleure lecture du fichier. 
<br><br>
Exemple de code : <br>
**\<!doctype html>**  <br>
*\<html\>* <br>
*\<\html\>*

**Erreur(s) à ne pas faire** : Ne pas oublier d'écrire cette balise et de la place au DÉBUT de tout document HTML. Sans cette balise, il n'est pas possible de faire valider notre site selon les normes W3C

## 2. \<html\>
La balise <html> représente la racine d'un document HTML. <br>
Cet élément est la première balise que l'on doit écrire après avoir défini le type de fichier. <br>
Tout autre élément du document doit être un descendant de cet élément.
<br><br>
Exemple de code : <br>
*\<!doctype html>* <br>
**\<html\>** <br>
**\<\html\>**

**Erreur(s) à ne pas faire** :

## 3. \<head\>
L'élément HTML \<head\> fournit des informations générales (métadonnées) sur le document, incluant son titre, scripts, et feuilles de style. Il ne peut y avoir qu'un seul élément \<head\> dans un document HTML.
<br><br>
Exemple de code : <br>
*\<!doctype html>* <br>
*\<html\>* <br>
**\<head\>** <br>
&nbsp; &nbsp; &nbsp; **\<meta charset="UTF-8" /\>** \<!-- *Définit l'ensemble de caractères utilisé pour afficher une page HTML* --\> <br>
&nbsp; &nbsp; &nbsp;**\<title\>Titre du document\</title\>** \<!-- *Titre de la page* --\> <br>
**\<\head\>** <br>
*\<\html\>* 

**Erreur(s) à ne pas faire** : Insérer des éléments autres que le titre de la page , scripts, et feuilles de style. Cela pourrait impacter négativement le référencement d'un site internet.


## 4. \<title\>
La balise <\title\> permet de définir le titre de la page ou plus précisement le titre de l'onglet.
<br><br>
Exemple de code : <br>
*\<!doctype html>* <br>
*\<html\>*
<br>
*\<head\>* <br>
&nbsp; &nbsp; &nbsp;**\<title\>** **Markdown Line Preview** **\<\title\>** <img width="169" height="28" alt="image" src="https://github.com/user-attachments/assets/8a36ddc3-a288-45f5-8a85-cd05d947fe20"/><br>
*\<\head\>* <br>
*\<\html\>* 

**Erreur(s) à ne pas faire** : Ne pas mettre un nom de page trop long. Si ce titre dépasse 60 caractères, tout le titre ne sera pas visible. De plus, cela pourrait impacter négativement le référencement.

## 5. \<body\>
La balise \<body\> est utilisée pour définir le corps d'une page HTML. Toutes les balises d'une page HTML doivent être à l'intérieur de cette balise.
<br><br>
Exemple de code : <br>
*\<!doctype html>* <br>
*\<html\>* <br>
*\<head\>* <br>
*\<title\>* <br>
*\<\title\>* <br>
*\<\head\>* <br>
**\<\body\>** <br>
&nbsp; &nbsp; &nbsp;**\<h1>Titre principal</h1\>**<br>
&nbsp; &nbsp; &nbsp;**\<h2>Titre secondaire</h2\>**<br>
&nbsp; &nbsp; &nbsp;**\<p>Texte aléatoire</p\>**<br>
**\<\body\>** <br>
*\<\html\>* 
