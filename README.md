# Euclid's _Elements_

There are [many editions of Euclid's _Elements_](index.html#editions).

This edition of _Elements_ is built using HTML, CSS, and Typescript.

The central content is in [index.html](index.html) with the format and semantics described in the [appendix about structure and semantics](index.html#structure_semantics).
The HTML in [index.html](index.html) is intentionally unstyled and provides no CSS- or Javascript-based functionality.
Other files can use this file as source code for the contents of <cite>Elements</cite> to create beautiful and interactive experiences. It is hoped that other authors can build new editions using the data in this file.

The web technology stack is the most widely deployed and mature open software platform in the world. This website is built with no runtime dependencies other than a recent standards-compliant web browser so that the software and code are useful and accessible to the widest array of people possible. It is straightforward to view and understand the source code as well as to contribute. Try the "View Source" command or open the developer tools in your browser to explore and make modifications. To learn more about web technology, see [MDN - the Mozilla Developer Network](https://developer.mozilla.org/). Development dependencies are minimized as much as possible while having some static analysis tooling for quality and developer ergonomic tooling for more comfort. 

## Build tools

[Vite](https://vitejs.dev/) is used for building the site. See `package.json` for details on the tools used.

- `npm run dev` - to develop the website with automatic refresh when files change
- `npm run build` - to build a static version of the website that can be deployed to any HTTP service that can serve static file content
- `npm run preview` - to preview the site build with `npm run build`
- `npm run clean` - to clean up built artifacts (deletes the files in the `public` directory which are built with `npm run build`)
