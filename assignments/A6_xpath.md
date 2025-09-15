# XPath

## Upload data package

We're gonna use a shortened sample from a project we have been working on, a web publication for the *Canoniser les Sept Sages de Rome* (C7S). We will use the first chapter of _Roman de Pelyarmenus_.

We have already created a [XAR](https://github.com/eeditiones/workshop/blob/master/data/xars/pelyarmenus-data-0.1.xar) file that you can download from the Git repository and install in your eXist-db via Dashboard > Package Manager

Open eXide (Dashboard > eXide) to enter your queries

### Accessing documents with doc() and collection()

`doc("/db/apps/pelyarmenus-data/data/registers/Index-Roman-de-Pelyarmenus.xml")`

vs

`collection("/db/apps/pelyarmenus-data/data/registers")//tei:TEI`

## XPath queries

* Get all person names (`persName` element) of the document 
* Get the <persName> elements that are a direct child of <person>
* Get the <persName> elements that have a @ref attribute
* Count how many <persName> elements have a @ref attribute and
* How many  <persName> elements do not have a @ref attribute 
* Get the <persName> elements whose @ref attribute is equal to “#Edypus2” 
* Get the <persName> element whose @ref attribute starts with “#Edypus”

**NB** useful functions to use here are `starts-with` and `count`. If you start typing a function name, eXide gives you an autocomplete selection of functions to choose from and their signatures

## Self-study

[Laks' Letters](https://github.com/eeditiones/workshop/blob/master/data/xars/laks-data-1.0.xar) is a selection of letters from the correspondence of Szymon Laks, currently being edited at Jagiellonian University. Think of queries you might want to run on this dataset.