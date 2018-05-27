# Underscore.js template compiler
Python utility to compile automatically to a javascript file all the underscore.js templates in a directory.

The script is constantly observing changes in some of the templates files. When some of the templates files are
edited, the script automatically compile all the templates in one javascript file.

## Usage
```
underscore_templates.py [-h] [-o OUTPUT] [--remove-whitespaces]
                               [--requirejs]
                               [--path-to-underscorejs PATH_TO_UNDERSCOREJS]
                               [--template-extension TEMPLATE_EXTENSION]
                               [--browser BROWSER]
                               [--evaluate-pattern EVALUATE_PATTERN]
                               [--escape-pattern ESCAPE_PATTERN]
                               [--interpolate-pattern INTERPOLATE_PATTERN]
                               template_dir

Compile all underscore templates in a directory

positional arguments:
  template_dir          Template directory

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Path to javascript file for writing the compiled
                        templates.
  --remove-whitespaces  Condense whitespaces
  --requirejs           Template should be requirejs compliant
  --path-to-underscorejs PATH_TO_UNDERSCOREJS
                        Path to underscore.js library
  --template-extension TEMPLATE_EXTENSION
                        Extension file of templates
  --browser BROWSER, -b BROWSER
                        Browser name
  --evaluate-pattern EVALUATE_PATTERN
                        Evaluate pattern
  --escape-pattern ESCAPE_PATTERN
                        Escape pattern
  --interpolate-pattern INTERPOLATE_PATTERN
                        Interpolate pattern
```
