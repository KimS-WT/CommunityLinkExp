# Changelog
- All notable changes to this project will be documented in this file.
- The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.7] - [Unreleased]
- This is the most recent version

### Notes for [0.2.7] - 2024-07-21
- Initial commit of experimental changes.
- Updated navbar layout and background color.
- Consolidated site.css for clarity.
- Research more on changelogs and "versioning"
- IndexPage template code from https://getbootstrap.com/docs/5.3/examples/carousel/

### Changed
- Changed navbar in _layout to better match template from above
- Changed spacerfromtop
- These changes affected other layouts on other pages

### Added
- Added to site.css to support IndexPage (bottom of site.css)
- Added code to footer in _layout

### Next Steps
- Continue refining the CSS for the index page.
- Experiment with different Bootstrap grid layouts for better content organization.
- Update the footer styling for consistency across all pages.
- Continue correcting Bootstrap and CSS layout and style
  - Fix the responsiveness of the rows 
    - About Page
    - Donate Page
  - Events dropdown text and arrow need to be darker
  - Research how to make scroll for navbar collapsed
  - Research Modals and how to style

# Previous Versions

## [0.2.7] - 2024-07-20
- This is a New Version of the project for experimentation 

### Notes for [0.2.7] - 2024-07-20
- I have changed several files and styles, the backend and things related to the database were untouched
- For example: Sign In page "layout" was unaffected only the navbar layout and HTML background color were affected.

### Changed
- Consolidated site.css for brevity clarity and functionality
- Consolidated _layout.cshtml.css for brevity clarity and functionality
- Overall these changes result in better use of Bootstrap and EF Core
  - Bootstrap is a grid system, and EF Core can display info from the database, (think tables, rows, columns)
- Implemented navbar with dropdown and search

### Next Steps
- Continue correcting Bootstrap and CSS layout and style
  - Fix the responsiveness of the rows 
    - About Page
    - Donate Page
  - Events dropdown text and arrow need to be darker
  - Research how to make scroll for navbar collapsed
  - Research Modals and how to style
