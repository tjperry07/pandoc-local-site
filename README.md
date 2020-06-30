## To run locally

1. Install [pandoc](https://pandoc.org/)
2. Intall Lunrjs or replace the `<script>` in [search.html](/docs/search.html).

Thats it. Open the index.html and play around.

## To build the search

Every time a new file is added or changed the index must be rebuilt.

1. Run `node build_index.js`

## Tools used

* https://gitlab.com/uvtc/rippledoc
* https://github.com/BLE-LTER/Lunr-Index-and-Search-for-Static-Sites