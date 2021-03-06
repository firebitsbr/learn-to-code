# Data formats

## CSV

- [Comma-separated values](https://en.wikipedia.org/wiki/Comma-separated_values) on Wikipedia.

### Implementation

- Python
    - [csv](https://docs.python.org/3/library/csv.html) - a built-in library.
- NodeJS
    - [csv](https://csv.js.org/) - an NPM package.
- PHP
    - [fgetcsv](https://www.php.net/manual/en/function.fgetcsv.php) function manual. See also [tutorial](https://phpenthusiast.com/blog/parse-csv-with-php) that uses it.
    - [str_getcsv](https://www.php.net/manual/en/function.str-getcsv.php) function manual.
- Shell
    - [Bash Read Comma Separated CSV File on Linux / Unix](https://www.cyberciti.biz/faq/unix-linux-bash-read-comma-separated-cvsfile/) tutorial.
    - `awk` command
        - [Using AWK to work with CSV files](https://newfivefour.com/awk-csv-files.html)
        - [Using awk command for .csv file](https://www.unix.com/shell-programming-and-scripting/124886-using-awk-command-csv-file.html)
    - `gawk` command
        - [Reading files](https://www.gnu.org/software/gawk/manual/html_node/Reading-Files.html) on GNU docs.
    - `sed` command
        - [sed - 10 examples to replace / delete / print lines of CSV file ](https://www.theunixschool.com/2013/02/sed-examples-replace-delete-print-lines-csv-files.html)
        - [sed FAQ - How do I parse a comma-delimited (CSV) data file?](https://www.linuxtopia.org/online_books/linux_tool_guides/the_sed_faq/sedfaq4_005.html)


## JSON

- [json.org](https://www.json.org)
- [JSON](https://www.w3schools.com/js/js_json_intro.asp) on W3 Schools.

If you search "json converter" in a search engine you'll find plenty of websites and browser extensions for converting or prettifying JSON.

### Variations or extensions of JSON

- [Jsonnet](https://jsonnet.org/)
- [JSONP](https://www.w3schools.com/js/js_json_jsonp.asp)
- [HJSON]()
- [JSON5]()

### Implementation

- Python
    - [json](https://docs.python.org/3/library/json.html)
        - Builtin library.
        - Can also be used as a command-line tool to validate and pretty-print JSON. See [json.tool](https://docs.python.org/3/library/json.html#module-json.tool) docs.
            ```sh
            $ echo '{"json": "obj"}' | python -m json.tool
            {
                "json": "obj"
            }
            ```
- NodeJS
    - [json](https://github.com/trentm/json)
        - NPM library for use on command-line.
        - Parse JSON text such as from a file and return requested data. Example:
            ```sh
            $ echo '{"fred":{"age":42}}' | json fred.age
            ```

## XML

- [XML](https://en.wikipedia.org/wiki/XML) on Wikipedia.


## HTML

See [guide](/Web%20dev/HTML) in this project.
