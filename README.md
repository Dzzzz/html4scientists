HTML4Scientists
================

 A html framework for scientists who is not so familiar with the most recent html techniques.



### How to use


#### General web pages

Use the template.html in template folder to create your own page general page template. Then copy the menu and footer code into every other pages.


Things to change

* Favicon (You can keep mime if you want. The defaul is a Omega + Lambda, which indicates one of the most interesting topic in physics.)
* All the codes with []
* Check the links
* Sync the menu and footer codes between pages


Refer to [HTML Kickstart](http://www.99lime.com/elements/) for more instructions about the built in elements.




#### Publication list


Publication list is one of the most useful features in this template. You can find the following two files in template/publication folder.

1. publication.html
2. publication-fromfile.html

The first one is the template for rendering inhtml bib contents. Add your bib contents in the html where we marked explicitly with ascii art.

publication-fromfile.html is a template for loading your publications.bib file with js and generate a publication table just like the other one. The good thing about using a different publications.bib file for your records is that you do not need to modify the html to add more publications. However, the draw backs of this is that the publication list can't be shown in a browser without js support (which is really rare these days). 

Refer to [bib publication list](https://github.com/vkaravir/bib-publication-list) for more information.


### Licenses

[HTML4Scientists](https://github.com/GuokrUnion/html4scientists) is licensed under MIT license. This framework is built with HTML KickStart (Joshua Gatcke http://www.99lime.com | HTML KickStart) which is also [released under MIT Open Source license](https://github.com/joshuagatcke/HTML-KickStart#html-kickstart-is-free-and-open-source). 
