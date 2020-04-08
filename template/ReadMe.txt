A quick overview of the files included in this folder:

proj_template.Rmd is the template Rmd file. It is set up to use bibtex style references, the github link, and css styling.

github.html is a html that links to our repo, and called in the Rmd file and is a little banner at the top right, when you look at the proj_template.html.

styles.css is a css file so that we can customize the styling. So far the only change that has been made is to block quotes. In order to use the change to blockquotes you would write the following in your Rmd file:

<div class="quote-container">

> Write your sample text here.

</div>

bibliography.bib is where we can save bibtex style citations. I have included a sample reference in there already, as a template guide. References will appear in the Rmd file after # References. They are included automatically in the output html file, but only if you have used the reference in your Rmd file. You can call a reference by writing [@citation_label] in your Rmd file.

Here is an example citation that should go into bibliography.bib:

@misc{ citation_label,
       author = "{Last Name, First Name and others}",
       title = "{My Article}",
       year = "2006" }

For more help with bibtext you can ask me to format it, or check out this link:
https://www.overleaf.com/learn/latex/bibliography_management_with_bibtex

american-institute-of-physics.csl specifies the citation style as (currently) APS. We will change this based on the citation style the professor prefers. 
