# Config

This is a lightweight package, designed to evolve over time as I find rules and tools that I like more, meant to standardize the way I code.

### ESlint

JavaScript rules are based off of Airbnb's `airbnb-base`, with a few custom rules that I like to change, or suppress.

### Stylelint

Utilizes Stylelint's basic build, but assumes and extends `stylelint-config-sass-guidelines` as the starting point. Minimal rules updated, at the moment.

### .gitignore

Always ignore `node_modules`.

### `package.json`

Most basic file possible to support above.


### To do:

I plan to add webpack and babel config files in the future. Babel will be utilized to transcompiler ES6, and webpack to provide a comprehensive build package that takes linted and transcompiled JS, linted SCSS, and other files, minify them as appropriate, and build them to a `dist/` directory.