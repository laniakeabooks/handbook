# Laniakea Books Handbook

## Book production

1. Acquire book text in any form.
    * title
    * subtitle
    * blurb
    * author bio
1. Decide book dimensions
1. Typeset book
    * Affinity Publisher / Adobe InDesign
    * TeX / Tectonic
    * typst
1. Decide paper gsm and calculate spine width
1. Design cover
    * front
    * back
    * insides
    * spine
1. Decide number of copies
1. Get quotes from printers
1. Decide retail price
1. Issue and assign ISBN
    * https://www.nielsenisbnstore.com/
1. Supply book data
    * https://www.nielsentitleeditor.com/
1. Produce HTML files and create epub
1. Add book files on website

## Coding practices

* All our code is licensed under MIT.
* All book assets are stored inside dedicated repositories with the prefix `book-` inside our [GitHub org](https://github.com/laniakeabooks/).
* We aim to maintain a minimal set of dependencies across our work.

## TeX

* We use the [tectonic](https://github.com/tectonic-typesetting/tectonic) distribution of TeX.
    * Tectonic is a XeTeX distribution, which brings some kind of [limitations](https://github.com/tectonic-typesetting/tectonic/issues/931).

## EPUB

* We follow the [EPUB 3.3 specification](https://www.w3.org/TR/epub-33/).
* We compile using Zip 3.0 (July 5th 2008), by Info-ZIP, bundled with macOS.
    * With `-X` attribute: Do  not save extra file attributes (Extended Attributes on OS/2, uid/gid and file times on Unix).
