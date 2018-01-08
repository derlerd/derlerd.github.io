# Jekyll Environment for My Academic Website

This repository contains the Jekyll environment, which is used to automatically generate my personal academic website hosted on github pages ([link](http://derlerd.github.io)).

## Publication List

To automatically generate the list of publications, the Jekyll post engine is used. That is, each file in the directories `_preprints`, `_proc`, `_jour`, `_articles`, `_talk`, `_theses`, `_deli` is treated as a single publication of the respective category. The date prefix is not displayed and only used for sorting purposes. The meta-information determines the displayed information. The key `layout` needs to be set to `post` and the remaining keys have the following semantics:
  * `year`: Publication year
  * `title`: Title of the publication
  * `authors`: A comma separated list of authors
  * `venue`: The publication venue
  * `vurl` (optional): An url for further information about the publication venue
  * `vatt` (optional): Additional attributes for the publication venue
  * `pdf` (optional): An url to the pdf file.
  * `pub` (optional): An url to the original publication.
  * `web` (optional): An additional weblink.
  * `bib` (optional): An url to a bibfile.
  * `talk` (optional): An url to the presentation slides.
  * `github` (optional): An url to a github repository. 

## License

The license for the code is inherited from [orderedlist/minimal](https://github.com/orderedlist/minimal), which was used as the basis for the theme. That is, the code is licensed under [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).
