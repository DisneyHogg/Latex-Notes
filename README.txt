The following set of files are notes and documents I have worked on during my time of my PhD, and earlier. The purpose of the repo is to allow for collaboration with my supervisor (Prof. Harry Braden) while I am avoiding using Overleaf.
My hope is to extend the use of the Notes directory to allow people who read my notes to suggest updates.
I need to find someway to protect the files from un-authorised editing. This is a priority. 
The work in 'Geodesics of Quadrics' should be protected from public viewing for now I guess, and I want to hide contact information in the CV, but otherwise there is no personal data which needs protecting.
I use texlive as my compiler (currently using the 2017 repository). This I edit with texstudio currently. 

The current architecture is as such:

header.sty
This is my big header file that I use in almost all my Latex documents (bar maybe my CV). 
It has a modification (header-colourful) which adds some (what I think are pretty) colours to the notes. 

library.bib
An out of date .bib file (DELETE IT) 

bib/
This is a directory containing my bibliography created by Mendeley (library.bib), a manually created .bib file for when I need to work around Mendeley (manual.bib) and a custom bibliography style I created using makebst (insert linke here) (obviously named as custom-bib-style.bst)

CV/
I assume this is my CV. I need to work out a way to protect that information.

'Example sheets and assignments'/
This is work I have typed up for any courses. I do not particularly use it often. 

'Geodesics of Quadrics'/
The main project I am currently working on with Harry. 
Has its own .bib file in it currently, which is out of date. (DELETE IT). 
Has its own header.sty file in it currently, which is out of date (DELETE IT).

Notes/ 
Notes I have written on a bunch of topics. 
Has its own .bib file in it currently, which is out of date. (DELETE IT).

Teaching/
Documents I have written to aid with teaching or presentations
Has its own header.sty file in it currently, which is out of date (DELETE IT).
