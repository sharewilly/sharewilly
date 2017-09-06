---
layout: post
title:  "Installieren & loslegen"
date:   2017-09-06
---

### Sharewilly WP
Sharewilly WP ist ein kostenfreies WordPress-Plugin der Münnecke & Vollmers GbR. Mit Sharewilly WP können deine Webseitenbesucher deine Beiträge und Webseiten in den Sozialen Medien teilen.  

* Sharing-Buttons für Facebook, Google+, Twitter, LinkedIn, XING & Pinterest
* Für die Buttons haben wir ausschliesslich statische Links verwendet - kein JavaScript!

  `Beispiel: http://www.facebook.com/sharer.php?u=<URL>&p[title]=<TITLE>`
  
* Sharewilly WP ist effizient, schlank und schnell.
* Wir tracken nicht! Sharewilly WP respektiert deine Privatspäre.
* Sharewilly gibt es auch in der PRO-Version

### Download
Github has a [guide here](https://help.github.com/articles/creating-project-pages-manually/) for manually setting up a new project page.

### Installieren
Clone or download the .zip of this repository and copy the files onto your pages branch. To preview the page before
pushing it live, run `bundle install` and when this is complete `jekyll serve --watch` from your pages folder. 
You can now visit http://localhost:4000 to view the page.

### Anpassen
To change the colourscheme and font stack, open `css/main.scss` in your editor and configure the variables defined there:

{% highlight scss %}
$primary-colour: #36C7C2 !default;
$primary-colour-dark: #0094A5 !default;

$secondary-colour: #631A44 !default;
$secondary-colour-dark: #441D4B !default;

$body-colour: #FAFAFA !default;
$copy-colour: #30485F !default;
$header-colour: $primary-colour-dark !default;

$font-stack: 'Lato', sans-serif !default;
{% endhighlight %}
