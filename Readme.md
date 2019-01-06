# P5 js examples

## Libs

* stored in `libs`

## Library type informations

* stored in `libs_types`
* Where to get:
    * `p5.js`:
        * go to [p5.ts](https://github.com/p5-types/p5.ts)
        * clone
        * follow instructions
    * `rambda`:
        ```bash
        npm install @types/ramda --save-dev
        ```
* reference libraries in at top javascript files
    * E.g. see [koch_snowflake](koch_snowflake/sketch.js)

    ```javascript
    /// <reference path="../libs_types/p5/global.d.ts" />
    /// <reference path="../libs_types/ramda/index.d.ts" />
    ```