# Honours-Template
 A LaTeX template for UTas Honours and Postgraduate Students. Pre-configured for Conservatorium of Music students using Turabian 8th Edition.
 
 ## Preamble
 This is adapted from my Honours exegesis which I completed in 2019. I have not yet removed all of the content associated with it. Feel free to delete things as necessary.
 
 ## Prerequisites
 You need several things installed in order to use this template properly; I will list everything that *I* use in my workflow. I would suggest that you use my workflow, at least to start.
 
 ### Accounts
 * GitHub (Sign up for the GitHub Student pack to enable private repositories)
 * Zotero
 
 ### Software 
 * Perl ActiveState (for LaTeX compiling): https://www.perl.org/get.html
 * Git: https://git-scm.com/downloads
 * GitHub Desktop: https://desktop.github.com/
 * MikTeX: https://miktex.org/
 * Zotero: https://www.zotero.org/
 * Zotero BetterBibTeX: https://retorque.re/zotero-better-bibtex/installation/
 * VSCode: https://code.visualstudio.com/
 * VSCode LaTeX Workshop extension: https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop
 * VSCode Spell Check extension: https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
 
 Install in that order.
 
 ## Setting up
 1. Download as a .zip file, and unzip it where you would like the folder to live.
 2. Create a local respository in GitHub Desktop, selecting the unzipped folder.
 3. Commit the change, and publish the branch online.
 4. In Zotero, export your desired library of citations using `File > Export`, and select `Better BibLaTeX` as the file type. Check the `Keep Updated` box (that keeps your citations up to date as you add more), and then save the file as `citations.bib` in `/backmatter/` of the folder of the template.
 5. Boot up VSCode, and open the root directory of the folder.
 6. Change some stuff (like the title), and then navigate to the sidebar icon that says "TeX" (or alternatively, hit `Ctrl + Alt + B`) and `Build recipe` using `Recipe: pdflatex > Bibtex > pdflatex x2`. 
 7. You should have successfully built the file. Inspect `main.pdf` for the finished file! 
