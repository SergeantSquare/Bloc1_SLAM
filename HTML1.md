# HTML
À quoi servent les balises \<!doctype html\>, \<html\>, \<head\>, \<title\> et \<body\>.

## 1. \<!doctype html\>
Tout fichier HTML doit commencer par la balise \<!doctype html\>. <br>
Cela permet au navigateur de connaître le type de fichier qu'il va lire et donc  garantir la meilleure lecture du fichier. 
<br><br>
Exemple de code : <br>
**\<!doctype html>**

## 2. \<html\>
La balise <html> représente la racine d'un document HTML. <br>
Cet élément est la première balise que l'on doit écrire après avoir défini le type de fichier. <br>
Tout autre élément du document doit être un descendant de cet élément.
<br><br>
Exemple de code : <br>
*\<!doctype html>* <br>
**\<html\>** <br>
**\<\html\>**

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


## 4. \<title\>
La balise <\title\> permet de définir le titre de la page ou plus précisement le titre de l'onglet.
<br><br>
Exemple de code : <br>
*\<!doctype html>* <br>
*\<html\>*
<br>
*\<head\>* 
**\<title\>** **Markdown Line Preview** **\<\title\>** <img width="169" height="28" alt="image" src="https://github.com/user-attachments/assets/8a36ddc3-a288-45f5-8a85-cd05d947fe20"/>
*\<\head\>* <br> <br>
*\<\html\>* 


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
**\<h1>Titre principal</h1\>**<br>
**\<h2>Titre secondaire</h2\>**<br>
**\<p>Texte aléatoire</p\>**<br>
**\<\body\>** <br>
*\<\html\>* 
