# Awk Codeless Language Module for BBEdit

## What does it do?

It provides a bit of syntax highlighting and commenting ability for Awk scripts in [BBEdit](https://www.barebones.com/support/bbedit/), my favourite editor.

## Why?

It's nicer to read and the keywords get highlighted a bit better than the Unix Script language module.

## To use

Pop the plist into "~/Library/Application Support/BBEdit/Language Modules/", either by dropping the file there or, if you'd like to stay up to day with changes git clone, e.g.

    git clone https://github.com/yb66/BBEdit-Awk "~/The place I keep git projects/BBEdit-Awk"

Then create a link:

    ln "~/The place I keep git projects/BBEdit-Awk/Awk.plist" "~/Library/Application Support/BBEdit/Language Modules/"

In both cases BBEdit will require a restart. Files with the extension `.awk` will automatically be recognised as Awk.

## Licence

See LICENCE.txt


## Contributions welcome!

Anything I've missed or you think could be improved, just let me know.
