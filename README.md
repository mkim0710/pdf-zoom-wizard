[![Build Status](https://travis-ci.org/beatngu13/pdf-zoom-wizard.svg?branch=master)](https://travis-ci.org/beatngu13/pdf-zoom-wizard)

# PDF Zoom Wizard

A new and extended implementation of the [PDF Bookmark Wizard](https://bitbucket.org/beatngu13/pdfbookmarkwizard/) for bookmarks *and* links based on [iText](https://itextpdf.com/).

The [road map](#road-map) below shows the current project status. Release `v0.1.0` is a simple GitHub port of the former PDF Bookmark Wizard (`v0.0.4.1`) that offers the same functionality. Have a look at the [changelog](https://github.com/beatngu13/pdf-zoom-wizard/blob/master/CHANGELOG.md) for the changes in subsequent releases.

To see how to get started, check out the [wiki](https://github.com/beatngu13/pdf-zoom-wizard/wiki/).

## Road map

- [x] Convert to Maven project
- [x] Enhance build process with Travis CI
- [x] Add changelog and Semantic Versioning
- [ ] Tests (!)
- [ ] Create self-contained app
- [ ] Migrate to Java 9
- [ ] Refactor entire project
- [ ] Improve logging using SLF4J and Logback
- [ ] Add ControlsFX for (modal) dialogs
- [ ] Offer dynamically resizing GUI content
- [ ] Extract Wizard interface for new implementation with iText
- [ ] Implement zoom settings for links
