# Change Log

Updates made to the Alaska Region Metadata Guide

### Unreleased

### 20261023



- Restructure site organization for Quarto
- Re-create original table of contents
- Created:
  - CONTRIBUTING.md
  - /assets directory
  - /assets/source directory


- Updated files:
  - _quarto.yml 
  - .gitignore
  - index.md


- Moved contents from /.gitbook/assets/ to /assets/
- Deleted /.gitbook directory
- Replaced all references to ".gitbook/assets" with "/assets"
- Added "ak-forum-icon_200-tr.png" favicon


### 20261022
- Created files:
  - .gitignore
  - .nojekyll
  - _quarto.yml
  - CHANGELOG.md
  - code.json
  - README.md
- Renamed files:
  - LICENSE to LICENSE.md
  - original GitBook "README.md" to "index.md"


The "original-GitBook" branch was initially created by pushing from the original GitBook source repository using the command:

`git push https://github.com/USFWS/ak-metadata-guide gitbook-main:original-GitBook`

The branch was then force pushed to the new "dev" branch.


## 20261022 - v0.0.1
- Created "[ak-metadata-guide](https://github.com/USFWS/ak-metadata-guide)" repository in [USFWS GitHub organization](https://github.com/USFWS)
- Created "[original-GitBook](https://github.com/USFWS/ak-metadata-guide/tree/original-GitBook)" branch by pushing from source using command:
  - `git push https://github.com/USFWS/ak-metadata-guide gitbook-main:original-GitBook`
- Created "dev" branch, set as default, and force merged contents of "original-GitBook" branch
- Tagged "original-GitBook" branch as [v0.0.1](https://github.com/USFWS/ak-metadata-guide/releases/tag/v0.0.1)

