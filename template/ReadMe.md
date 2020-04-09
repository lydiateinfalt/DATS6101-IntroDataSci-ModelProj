# Brief overview of template

Here are the following files in this folder, and a brief description:

proj_template.Rmd
-----------------

This is the template Rmd style.
It specifies the bibliography file, bibliography style (APS), the github link, and the customized css styling.

proj_template.html
------------------

This is the html output file of proj_template.Rmd

github.html
-----------

This is a html file that points back to this repo, so that anyone opening our project template will be able to find our work.

styles.css
----------

This a css file for customized styling.
So far the only change has been made to blockquotes. Your final result for blockquotes in the output html file will look like the following:

<div class="quote-container">

> Write your sample text here.

</div>

american-institute-of-physics.csl
---------------------------------

This is a csl file. This file specifies the citation style. The current citation style is AIP/APS.

bibliography.bib
----------------

This is the bib file, where we can create and save bibtex style citations. I have included a sample reference in there already, as a template guide. References will appear in the Rmd file after # References. They are included automatically in the output html file, but only if you have used the reference in your Rmd file. You can call a reference by writing [@citation_label] in your Rmd file.

Here is an example citation that should go into bibliography.bib:

      @misc{ citation_label,
              author = "{Last Name, First Name and others}",
              title = "{My Article}",
              year = "2006" }
