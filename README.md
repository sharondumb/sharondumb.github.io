# Personal Website of Sharon Du

Here is the basic guide on how to use this. I have already cut down the functionality significantly, removing "news", "projects", "repositories", and other extra things (can add them back later).

## MAIN FILES:

* `_config.yml` -- this is where we need to fill out the basic information, such as email, website title, etc. I already did it.
* `_data/cv.yml` -- this is where the info to automatically generate your cv is located! We can fill it out
* `_bibliography/papers.bib` -- file with your published papers. We can cut this section completely.

## HOW TO EDIT THE PAGES

The files above should be edited rarely or just once. The main content of the file is located in the `_pages` folder. Right now, it contains the three pages that comprise your website: `about.md` (main one), `cv.md`, and `publications.md`. They are markdown files, which means that they are kind-of plain text, not LaTeX or code. They also contain some metadata at the top.

Markdown guide: [https://www.markdownguide.org](https://www.markdownguide.org)

Besides the three pages, there is also a `blog`. It's auto-generated, and the new posts have to be added to the `_posts` folder. The format is the same: you have metadata at the top, and markdown text throughout.

FINALLY, you can put ANY file (within reason) on the website: photos, pdfs, artworks, etc. You put them into the `assets` folder, and then link from the pages to them.

# HOW TO START EDITING

Variant one:

1 - Install VSCode: [https://code.visualstudio.com](https://code.visualstudio.com)

2 - download the code folder to your computer, open it with vscode 

3 - edit it locally, then "COMMIT" and "PUSH" the changes back to the server (it is better if i just show it)

Variant two: 

Use VSCode in the browser: [vscode.dev](vscode.dev) You will also have to log into github there, and everything will be done in the cloud!

Variant three:

Simpler edits can be done directly on github.com.
