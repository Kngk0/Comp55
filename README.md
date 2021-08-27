# comp55
Hi!  I've decided to make this repository to document changes that are made for COMP 55 over the years and to make the educational materials more collaborative.

More to come in the future about what's available and where

Special credit goes to the Pacific Students from COMP 129 in Spring of 2021 for editing and incorporating their changes into the repo.

I also [used pandoc](https://pandoc.org/getting-started.html) to switch files from word doc to github flavored markdown, the command that I used being:

```pandoc COMPLab1.docx -f docx -t gfm -s -o COMPLab1.md```
To extract the images embedded in the document, I like to have things in a flatter structure so you can skip everything after the ```&&```

```pandoc "COMPLab1.docx" --extract-media=defaultmedia && mv defaultmedia/media ./lab1media```
If defaultmedia does not exist, then it would create the folder, so you may have to remove it.
