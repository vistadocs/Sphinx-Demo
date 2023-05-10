Template for the Read the Docs tutorial
=======================================

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/

This repo has been integrated with a Read the Docs account to facilitate CI/CD

Process
========

Adding new MD files:

Add a new file to the docs folder of this repo. The markdowntext.md file is an example.

Open the index.rs file and add a reference to the new file in the Contents section.

Commit and push the changes.

Read the Docs will automatically generate the relevant html and pdf files for viewing and so after a period, navigate to https://sphinx-demo-vista.readthedocs.io/en/latest/index.html to see the changes

A single pdf document will be built from the added MD files. To see the PDF document, navigate to:

https://readthedocs.org/projects/sphinx-demo-vista/downloads/pdf/latest/


