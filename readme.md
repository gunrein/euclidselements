# Euclid's _Elements_

There are [many editions of Euclid's _Elements_](index.html#editions).

This edition of _Elements_ is built using HTML, CSS, and Typescript.

The central content is in [index.html](index.html) with the format and semantics described in the [appendix about structure and semantics](index.html#structure_semantics).
The HTML in [index.html](index.html) is intentionally unstyled and provides no CSS- or Javascript-based functionality.
Other files can use this file as source code for the contents of <cite>Elements</cite> to create beautiful and interactive experiences. It is hoped that other authors can build new editions using the data in this file.

The website is built with no runtime dependencies other than a recent standards-compliant web browser. Development dependencies are minimized as much as possible while having some static analysis tooling for quality and developer ergonomic tooling for more comfort.

The code and publishing approach are intended to make it easy to view and understand the source code as well as to contribute.

## Build tools

[Vite](https://vitejs.dev/) is used for building the site. See `package.json` for details on the tools used.

To develop the website with automatic refresh when files change, execute `npm run dev`.

To build a static version of the website, execute `npm run build`.

To preview the site, execute `npm run preview`.

To clean up built artifacts, execute `npm run clean`.
