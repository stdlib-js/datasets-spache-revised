<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Revised Spache

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> A [list][@klare:1974a] of simple American-English words (revised Spache).



<section class="usage">

## Usage

```javascript
import words from 'https://cdn.jsdelivr.net/gh/stdlib-js/datasets-spache-revised@deno/mod.js';
```

#### words()

Returns a [list][@klare:1974a] of simple American-English words (revised Spache).

```javascript
var data = words();
/* returns
    [
        'a',
        'able',
        'about',
        'above',
        ...
    ]
*/
```

</section>

<!-- /.usage -->

<section class="examples">

<!-- TODO: more creative example. -->

## Examples

<!-- eslint no-undef: "error" -->

```javascript
import floor from 'https://cdn.jsdelivr.net/gh/stdlib-js/math-base-special-floor@deno/mod.js';
import randu from 'https://cdn.jsdelivr.net/gh/stdlib-js/random-base-randu@deno/mod.js';
import words from 'https://cdn.jsdelivr.net/gh/stdlib-js/datasets-spache-revised@deno/mod.js';

var data = words();
var len = data.length;
var idx;
var i;

// Select random words from the list...
for ( i = 0; i < 100; i++ ) {
    idx = floor( randu()*len );
    console.log( data[ idx ] );
}
```

</section>

<!-- /.examples -->



* * *

<section class="references">

## References

-   Spache, George. 1953. "A New Readability Formula for Primary-Grade Reading Materials." _The Elementary School Journal_ 53 (7): 410–13. doi:[10.1086/458513][@spache:1953a].
-   Klare, George R. 1974. "Assessing Readability." _Reading Research Quarterly_ 10 (1). Wiley, International Reading Association: 62–102. <http://www.jstor.org/stable/747086>.
-   Stone, Clarence R. 1956. "Measuring Difficulty of Primary Reading Material: A Constructive Criticism of Spache's Measure." _The Elementary School Journal_ 57 (1). University of Chicago Press: 36–41. <http://www.jstor.org/stable/999700>.
-   Perera, Katherine. 2012. "The assessment of linguistic difficulty in reading material." In _Linguistics and the Teacher_, edited by Ronald Carter, 101–13. Routledge Library Editions: Education. Taylor & Francis. <https://books.google.com/books?id=oNXFQ9Gn6XIC>.

</section>

<!-- /.references -->

<!-- <license> -->

## License

The data files (databases) are licensed under an [Open Data Commons Public Domain Dedication & License 1.0][pddl-1.0] and their contents are licensed under [Creative Commons Zero v1.0 Universal][cc0]. The software is licensed under [Apache License, Version 2.0][apache-license].

<!-- </license> -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-spache-revised.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-spache-revised

[test-image]: https://github.com/stdlib-js/datasets-spache-revised/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/datasets-spache-revised/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-spache-revised/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-spache-revised?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-spache-revised.svg
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-spache-revised/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/datasets-spache-revised#cli
[cli-url]: https://github.com/stdlib-js/datasets-spache-revised/tree/cli
[@stdlib/datasets-spache-revised]: https://github.com/stdlib-js/datasets-spache-revised/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/datasets-spache-revised/tree/deno
[umd-url]: https://github.com/stdlib-js/datasets-spache-revised/tree/umd
[esm-url]: https://github.com/stdlib-js/datasets-spache-revised/tree/esm
[branches-url]: https://github.com/stdlib-js/datasets-spache-revised/blob/main/branches.md

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[@spache:1953a]: https://doi.org/10.1086/458513

[@klare:1974a]: http://www.jstor.org/stable/747086

</section>

<!-- /.links -->
