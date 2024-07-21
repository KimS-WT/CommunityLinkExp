# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.8] - 2024-7-20
 - This version has added to the IndexPage and changed the NavBar

### Notes
 - Research more on changelogs and "versioning"
 - IndexPage template code from https://getbootstrap.com/docs/5.3/examples/carousel/

### Changed
 - navbar in _layout to better match template from above
 - changed spacerfromtop
 - these changes affected other layouts on other pages

### Added
- added to site.css to support IndexPage (bottom of site.css)
- added code to footer in _layout

## [0.2.7] - 2024-7-20
 - This is a New Version of the project for experimentation 

### Notes
 - I have changed several files and styles, the backend and things related to the database were untoched
 - For Example: Sign In page "layout" was unaffected only the navbar layout and html background color were affected.

### Changed
 - consolidated site.css for brevity clarity and functionality
 - consolidated _layout.chtml.css for brevity clarity and functionality
 - overall these changes result in better use of bootstrap and ef-core
   - bootstrap is a grid system, and efcore can display info from the database, (think tables, rows, columns)
 - implemented navbar with dropdown and search

### Next Steps
 - continue correcting bootstrap and css layout and style
  - fix the responsiveness of the rows 
    - About Page
    - Donate Page
  - Events dropdown text and arrow needs to be darker
  - Research how to make scroll for navbar collapsed
  - Research Modals and how to style
