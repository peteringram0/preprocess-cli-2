preprocess-cli-2
================

CLI wrapper for [preprocess](https://github.com/jsoverson/preprocess).

Clone form qwtel/preprocess-cli-2, added in the ability to pass it a context object or a context
file (-e). If both are provided they will be merged and presented onto the FE in normal way.

Usage
-----
```
Usage: preprocess <file> [options]

Options:
  -o, --output-file                 Output file                                                               
  -s, --file-not-found-silent-fail  Instruct preprocess to fail silently.                                       [default: false]
  --src-dir                         The directory where to look for files included. Defaults to process.cwd().
  --src-eol                         The end of line (EOL) character to use for the preprocessed result.       
  -t, --type                        The syntax type of source string to preprocess.                             [default: "html"]
  -c, --context                     Context to provide must be a object wrapped in quotes (Must be provided or -e)
  -e, --env                         Environment file to load in (Path to JSON file) (Must be provided or -c)
```
