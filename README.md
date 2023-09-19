# difftool
Simple tool in Python to output the differences between two input files in HTML markup. Supports syntax highlighting for code. Requires python, difflib, argparse and pygments.

Usage: ```difftool.py File1 File2 Outfile [-h] [-L LANGUAGE] [-S STYLE] [-C1 COLOR] [-C2 COLOR] [-B1 COLOR] [-B2 COLOR] [-BG COLOR] [-N COLOR] [-F FONT]```

All positional arguments are required while all flags are optional.

E.g. ```difftool.py helloworld.py byeworld.py -L python -S emacs -BG lavender -F "11px monospace"```

More help: ```difftool.py -h```

Can also be imported as a python module and used via the 'diff' function.

Output HTML file can be viewed in any browser that supports HTML5 and CSS.

Supported languages for syntax highlighting: https://pygments.org/languages/

See pygments for more info on syntax highlighting.
