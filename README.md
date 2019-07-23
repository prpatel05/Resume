## Setup
1. `npm install`
1. `cp css/resume.css node_modules/markdown-resume/assets/css`
1. `cp template/default.html node_modules/markdown-resume/assets/templates`

__to generate PDF's you'll also need to install: [wkhtmltopdf](https://github.com/pdfkit/pdfkit/wiki/Installing-WKHTMLTOPDF)__.

## Generate
```shell
node node_modules/markdown-resume/bin/md2resume resume.md
mv resume.html index.html
node node_modules/markdown-resume/bin/md2resume --pdf resume.md
```
