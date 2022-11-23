# Porto Autumn School 2022

This repository is intended to be used to demo practical docs-as-code process in the Porto Autumn School 2022.

The DITA source files are taken from https://github.com/dita-ot/docs repository, which are licensed under the terms of its Apache License 2.0.

This repo also has an Apache License 2.0.

This repo has the following GitHub Actions:

- Docker-based DITA Open Toolkit build of the source files into uncustomized PDF
- Docker-based Aspell check of spelling in one file

## Contents of this repo

README.md - this file
License - Apache License 2.0 for this repo
taskbook.ditamap - ditamap used as input for building the documentation.
  - taskbook - folder with the dita files required for the document
  - .github 
    - workflows
      - blank.yml -YAML file that provides instructions for the GitHub Action used to build the PDF
