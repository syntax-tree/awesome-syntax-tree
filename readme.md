<!--lint disable no-html maximum-line-length-->

# awesome syntax-tree [![awesome][awesome-badge]][self]

[<img src="https://raw.githubusercontent.com/syntax-tree/unist/b187eb7/logo.svg?sanitize=true" align="right" alt width="200">](https://unified.js.org)

> A curated list of awesome syntax-tree, [**unist**][unist], [**mdast**][mdast]
> (Markdown), [**hast**][hast] (HTML), and [**nlcst**][nlcst] (prose) resources.

**syntax-tree** is an organization housing [**unist**][unist] and its main
implementations [**mdast**][mdast], [**hast**][hast], and [**nlcst**][nlcst].
[**unist**][unist] is a specification for syntax trees that comes with a big
ecosystem of utilities in JavaScript for working with those trees.
On top of [**unist**][unist] and its implementations sits the rest of
[**unified**][unified] that does all kinds of things to process content.

## Contents

* [Official](#official)
* [unist utilities](#unist-utilities)
* [mdast utilities](#mdast-utilities)
* [hast utilities](#hast-utilities)
* [nlcst utilities](#nlcst-utilities)
* [Related lists](#related-lists)
* [License](#license)

## Official

* [syntax-tree](https://github.com/syntax-tree) - Organization.
* [unist](https://github.com/syntax-tree/unist) - **unist** specification.
* [mdast](https://github.com/syntax-tree/mdast) - **mdast** (Markdown) specification.
* [hast](https://github.com/syntax-tree/hast) - **hast** (HTML) specification.
* [nlcst](https://github.com/syntax-tree/nlcst) - **nlcst** (prose) specification.
* [unified](https://github.com/unifiedjs/unified) - Ecosystem.
* [unified.js.org](https://unified.js.org) - Ecosystem website.

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
* [hast-util-find-and-replace](https://github.com/syntax-tree/hast-util-find-and-replace) - Find and replace text in a tree.
* [hast-util-sanitize](https://github.com/syntax-tree/hast-util-sanitize) - Sanitize a tree.
* [hast-util-select](https://github.com/syntax-tree/hast-util-select) - `querySelector`, `querySelectorAll`, and `matches`.
* [hast-util-has-property](https://github.com/syntax-tree/hast-util-has-property) - Check if a node has a property.
* [hast-util-is-element](https://github.com/syntax-tree/hast-util-is-element) - Check if a node is a (certain) element.
* [hast-util-assert](https://github.com/syntax-tree/hast-util-assert) - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/hast#list-of-utilities)

## nlcst utilities

* [nlcst-search](https://github.com/syntax-tree/nlcst-search) - Search for patterns in a tree.
* [nlcst-to-string](https://github.com/syntax-tree/nlcst-to-string) - Transform to a string.
* [nlcst-is-literal](https://github.com/syntax-tree/nlcst-is-literal) - Check if a node is meant literally.
* [nlcst-normalize](https://github.com/syntax-tree/nlcst-normalize) - Normalize a word for easier comparison.
* [nlcst-test](https://github.com/syntax-tree/nlcst-test) - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/nlcst#list-of-utilities)

## Related lists

* [awesome unified](https://github.com/unifiedjs/awesome)
* [awesome remark](https://github.com/remarkjs/awesome-remark)
* [awesome rehype](https://github.com/rehypejs/awesome)
* [awesome retext](https://github.com/retextjs/awesome)
* [awesome mdx](https://github.com/transitive-bullshit/awesome-mdx)

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

[mdast]: https://github.com/syntax-tree/mdast

[nlcst]: https://github.com/syntax-tree/nlcst
