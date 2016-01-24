# main-bower-files-cli

Command-line runner for [main-bower-files library](https://github.com/ck86/main-bower-files).

It`s useful for building front-end project with command-line tools.

Example:

    cat $(./node_modules/.bin/main-bower-files-cli | grep "\.js$") | ./node_modules/.bin/uglifyjs -
