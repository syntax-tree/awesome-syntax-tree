<!--lint disable no-html maximum-line-length-->

# awesome syntax-tree [![awesome][awesome-badge]][self]

[<img src="https://raw.githubusercontent.com/syntax-tree/unist/b187eb7/logo.svg?sanitize=true" align="right" alt width="200">](https://unifiedjs.com)

> A curated list of awesome syntax-tree, **[unist][]**, **[mdast][]**
> (markdown), **[hast][]** (HTML), **[xast][]** (XML), **[esast][]** (JS), and
> **[nlcst][]** (prose) resources.

**syntax-tree** is an organization housing **[unist][]** and its main
implementations **[mdast][]**, **[hast][]**, **[xast][]**, **[esast][]**, and
**[nlcst][]**.
**[unist][]** is a specification for syntax trees that comes with a big
ecosystem of utilities in JavaScript for working with those trees.
On top of **[unist][]** and its implementations sits the rest of
**[unified][]** that does all kinds of things to process content.

## Contents

* [Official](#official)
* [unist utilities](#unist-utilities)
* [mdast utilities](#mdast-utilities)
* [hast utilities](#hast-utilities)
* [xast utilities](#xast-utilities)
* [esast utilities](#esast-utilities)
* [nlcst utilities](#nlcst-utilities)
* [Related lists](#related-lists)
* [License](#license)

## Official

* [syntax-tree](https://github.com/syntax-tree) - Organization.
* [unist](https://github.com/syntax-tree/unist) - **unist** specification.
* [mdast](https://github.com/syntax-tree/mdast) - **mdast** (markdown) specification.
* [hast](https://github.com/syntax-tree/hast) - **hast** (HTML) specification.
* [xast](https://github.com/syntax-tree/xast) - **xast** (XML) specification.
* [esast](https://github.com/syntax-tree/esast) - **esast** (JS) specification.
* [nlcst](https://github.com/syntax-tree/nlcst) - **nlcst** (prose) specification.
* [unified](https://github.com/unifiedjs/unified) - Ecosystem.
* [unifiedjs.com](https://unifiedjs.com) - Ecosystem website.

## unist utilities

* [unist-builder](https://github.com/syntax-tree/unist-builder) - Create trees with a nice syntax.
* [unist-util-is](https://github.com/syntax-tree/unist-util-is) - Check if a node passes a test.
* [unist-util-visit](https://github.com/syntax-tree/unist-util-visit) - Visit nodes.
* [unist-util-map](https://github.com/syntax-tree/unist-util-map) - Create a new tree by mapping all nodes.
* [unist-util-filter](https://github.com/syntax-tree/unist-util-filter) - Create a new tree with nodes that pass a filter.
* [unist-util-remove](https://github.com/syntax-tree/unist-util-remove) - Remove nodes from a tree.
* [unist-util-select](https://github.com/syntax-tree/unist-util-select) - Select nodes with CSS-like selectors.
* [unist-util-inspect](https://github.com/syntax-tree/unist-util-inspect) - Inspect nodes.
* [unist-util-assert](https://github.com/syntax-tree/unist-util-assert) - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/unist#list-of-utilities)

## mdast utilities

* [mdast-util-to-hast](https://github.com/syntax-tree/mdast-util-to-hast) - Transform to hast.
* [mdast-util-to-nlcst](https://github.com/syntax-tree/mdast-util-to-nlcst) - Transform to nlcst.
* [mdast-util-to-string](https://github.com/syntax-tree/mdast-util-to-string) - Get the plain text content of a node.
* [mdast-util-definitions](https://github.com/syntax-tree/mdast-util-definitions) - Find definitions.
* [mdast-util-toc](https://github.com/syntax-tree/mdast-util-toc) - Generate a Table of Contents.
* [mdast-normalize-headings](https://github.com/syntax-tree/mdast-normalize-headings) - Fix heading depths.
* [mdast-util-heading-range](https://github.com/syntax-tree/mdast-util-heading-range) - Use heading as ranges.
* [mdast-zone](https://github.com/syntax-tree/mdast-zone) - Use comments as ranges and markers.
* [mdast-util-assert](https://github.com/syntax-tree/mdast-util-assert) - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/mdast#list-of-utilities)

## hast utilities

* [hastscript](https://github.com/syntax-tree/hastscript) - Create trees with a nice syntax.
* [hast-to-hyperscript](https://github.com/syntax-tree/hast-to-hyperscript) - Transform to something else (React, Vue, etc).
* [hast-util-from-dom](https://github.com/syntax-tree/hast-util-from-dom) - Transform from a DOM tree.
* [hast-util-from-text](https://github.com/syntax-tree/hast-util-from-text) - Set plain-text content.
* [hast-util-to-dom](https://github.com/syntax-tree/hast-util-to-dom) - Transform to a DOM tree.
* [hast-util-to-html](https://github.com/syntax-tree/hast-util-to-html) - Transform to an HTML string.
* [hast-util-to-mdast](https://github.com/syntax-tree/hast-util-to-mdast) - Transform to mdast.
* [hast-util-to-nlcst](https://github.com/syntax-tree/hast-util-to-nlcst) - Transform to nlcst.
* [hast-util-to-text](https://github.com/syntax-tree/hast-util-to-text) - Get plain-text content.
* [hast-util-to-xast](https://github.com/syntax-tree/hast-util-to-xast) - Transform to xast.
* [hast-util-find-and-replace](https://github.com/syntax-tree/hast-util-find-and-replace) - Find and replace text in a tree.
* [hast-util-sanitize](https://github.com/syntax-tree/hast-util-sanitize) - Sanitize a tree.
* [hast-util-select](https://github.com/syntax-tree/hast-util-select) - `querySelector`, `querySelectorAll`, and `matches`.
* [hast-util-has-property](https://github.com/syntax-tree/hast-util-has-property) - Check if a node has a property.
* [hast-util-is-element](https://github.com/syntax-tree/hast-util-is-element) - Check if a node is a (certain) element.
* [hast-util-assert](https://github.com/syntax-tree/hast-util-assert) - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/hast#list-of-utilities)

## xast utilities

* [xastscript](https://github.com/syntax-tree/xastscript) - Create xast trees.
* [xast-util-feed](https://github.com/syntax-tree/xast-util-feed) - Build a feed (RSS, Atom).
* [xast-util-from-xml](https://github.com/syntax-tree/xast-util-from-xml) - Transform from an XML string.
* [xast-util-sitemap](https://github.com/syntax-tree/xast-util-sitemap) - Build a sitemap.
* [xast-util-to-xml](https://github.com/syntax-tree/xast-util-to-xml) - Transform to an XML string.

[Find more utilities »](https://github.com/syntax-tree/xast#list-of-utilities)

## esast utilities

* [estree-util-attach-comments](https://github.com/syntax-tree/estree-util-attach-comments) - Attach comments to the tree.
* [estree-util-build-jsx](https://github.com/syntax-tree/estree-util-build-jsx) - Turn JSX into function calls.
* [esast-util-from-js](https://github.com/syntax-tree/esast-util-from-js) - Transform from a JavaScript string.
* [estree-util-to-js](https://github.com/syntax-tree/estree-util-to-js) - Transform to a JavaScript string.
* [estree-util-value-to-estree](https://github.com/remcohaszing/estree-util-value-to-estree) - Turn a JavaScript value into an estree expression

[Find more utilities »](https://github.com/syntax-tree/esast#list-of-utilities)

## nlcst utilities

* [nlcst-search](https://github.com/syntax-tree/nlcst-search) - Search for patterns in a tree.
* [nlcst-to-string](https://github.com/syntax-tree/nlcst-to-string) - Transform to a string.
* [nlcst-is-literal](https://github.com/syntax-tree/nlcst-is-literal) - Check if a node is meant literally.
* [nlcst-normalize](https://github.com/syntax-tree/nlcst-normalize) - Normalize a word for easier comparison.
* [nlcst-test](https://github.com/syntax-tree/nlcst-test) - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/nlcst#list-of-utilities)

## Related lists

* [awesome unified](https://github.com/unifiedjs/awesome-unified)
* [awesome remark](https://github.com/remarkjs/awesome-remark)
* [awesome rehype](https://github.com/rehypejs/awesome-rehype)
* [awesome retext](https://github.com/retextjs/awesome-retext)
* [awesome mdx](https://github.com/mdx-js/awesome)

## License

[![CC-BY][license-badge]][license] © [Titus Wormer][author]

<!-- Definitions. -->

[license]: https://creativecommons.org/licenses/by/4.0/

[license-badge]: https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by.svg

[author]: https://wooorm.com

[awesome-badge]: https://awesome.re/badge.svg

[self]: https://github.com/remarkjs/awesome-remark

[unified]: https://github.com/unifiedjs/unified

[unist]: https://github.com/syntax-tree/unist

[hast]: https://github.com/syntax-tree/hast

[xast]: https://github.com/syntax-tree/xast

[esast]: https://github.com/syntax-tree/esast

[mdast]: https://github.com/syntax-tree/mdast

[nlcst]: https://github.com/syntax-tree/nlcst
