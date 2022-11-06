# Page_de_garde
<p>

This repository aim at creating a title page in TeX for my lab report at UTBM <br>
It was greatly inspired by the work of [Dorian Depriestier](https://gist.github.com/DorianDepriester/c7b4ff58ef4973bf5c85)<br>
This repository is composed of 2 files, with one just being an example of the usage of the true file `page_de_garde` 

</p>

# How to use this file ?
<p>

First, you'll need 3 package on your system these are : 
* `fancybox`
* `graphicx`
* `color`
</p>
<p>

Then, just include the `page_de_garde` file in your project with the command `\input{page_de_garde.tex}` that need to be just after the inclusion of all your package. Then use the command `\pagedegarde`or `\pagdegardeboxed` just after `\begin{document}` to create the title page. <br>
In order to work proprely, you nedd to pass few argument to `page_de_garde` : 
* `\UV` : UV code 
* `\nomUV`: name of the UV 
* `\contenu`: file content, or file title
* `\semestre`: semester name or date 
* `\AU` : school year 
* `\couleuracc` : accentuation color of the title, there are 19 color name included in the `color` package 
  
</p>
