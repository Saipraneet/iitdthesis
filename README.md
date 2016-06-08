# A template for thesis at Indian Institute of Technology Delhi

A latex template for Masters (MTech, Dual), Doctorate (PhD), MS or Bachelors(BTech) theses at IIT Delhi.
## Files
A LaTeX class (iitddiss.cls) along with a simple template thesis
(thesis.tex) and synopsis (synopsis.tex) are provided here.  These can
be used to easily write a thesis (or synopsis) suitable for submission
at IIT-Delhi.  The class provides options to format PhD, MS,
M.Tech. and B.Tech. thesis.  It also allows one to write a synopsis
using the same class file.  Also provided is a BIBTeX style file
(iitd.bst) that formats all bibliography entries.  A simple sample bibliography file (refs.bib) is also
provided.

For convenience, also included is Stephan I. B"ottcher's lineno
package that allows one to add line numbers to each line of a LaTeX
document.


## Compiling
Compile the sample thesis like so if using the terminal or in your favorite latex editor

```{r, engine='bash', count_lines}
pdflatex thesis.tex
bibtex thesis
pdflatex thesis.tex
pdflatex thesis.tex
```

## Credits
This has been adpated from "https://www.sharelatex.com/templates/thesis/indian-institute-of-technology-madras-thesis" by Prabhu Ramachandran. 
