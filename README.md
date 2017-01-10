# open_refine_bibtex

This repository contains code snippets needed for templating Open Refine cleaned citation data to produce a bibtex formatted file.

## Usage

Access the open refine templating option by clicking on Export (in the upper right hand portion of your screen) and clicking Templating...  Delete everything in the Prefix and Suffix fields, and copy the contents of row_template.txt into the Row Template field.  Delete everything in the Row Separator field and then press Enter to add a blank line.  You won't see the blank line in the field, but you'll get a correctly formatted file in the preview pane on the right.  Click Export and you'll get a .txt file and you can manually change the extension to .bib.

## In Development

This template is very new and only supports the following Article fields:
- Author
- Title
- Journal
- Year
- Volume
- Pages
- DOI
