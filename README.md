```
Project name: search
Description: A script to search files based on include and exclude patterns using ripgrep.
             By default, searches are case-insensitive. Use -c to make them case-sensitive.
Version 1.0
Created by Lawrence Lagerlof as a proof of concept
Engineered by o1-mini

Usage: search [options]

Options:
  -t TYPE         File type to search (e.g., php, python)
  -i INCLUDE      Include string (can be used multiple times)
  -e EXCLUDE      Exclude string (can be used multiple times)
  -c              Enable case-sensitive search (default is case-insensitive)
  --help          Display this help message

Examples:
  search -t php -i tmpl_open -e load_php_templates
  search -t php -i tmpl_open -i load_php_templates
  search -t php -i tmpl_open
  search -t python -e "my text"
  search -c -t java -i Main -e "deprecatedMethod"
```
