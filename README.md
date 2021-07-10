# difftool
Outputs the differences between two input files in HTML markup. Supports syntax highlighting for code. Requires python, difflib, argparse and pygments.

usage: python difftool.py [-h] [-L LANGUAGE] [-S STYLE] [-C1 COLOR] [-C2 COLOR] [-B1 COLOR] [-B2 COLOR] [-BG COLOR] [-N COLOR]
                   File1 File2 Outfile

Outputs the differences between two input files in HTML markup. Requires difflib, argparse and pygments.

positional arguments:
  File1                 First file to compare.
  File2                 Second file to compare.
  Outfile               File to write HTML output to.

optional arguments:
  -h, --help            show this help message and exit
  -L LANGUAGE, -l LANGUAGE, --lang LANGUAGE, --language LANGUAGE
                        Syntax highlighting for specified programming language (format: LANGUAGE), file extension type
                        (format: *.EXTENSION), or MIME type (format: TYPE/SUBTYPE). Default is no syntax highlighting.
  -S STYLE, -s STYLE, --style STYLE
                        Syntax highlighting style. Default is xcode.
  -C1 COLOR, -c1 COLOR, --color1 COLOR
                        Color to highlight differences in the first file with. HTML color name or HEX value. Default
                        is lightpink.
  -C2 COLOR, -c2 COLOR, --color2 COLOR
                        Color to highlight differences in the second file with. HTML color name or HEX value. Default
                        is lightgreen.
  -B1 COLOR, -b1 COLOR, --bg1 COLOR
                        Background color of leftmost column. HTML color name or HEX value. Default is white.
  -B2 COLOR, -b2 COLOR, --bg2 COLOR
                        Background color of middle (line number) column. HTML color name or HEX value. Default is
                        whitesmoke.
  -BG COLOR, -B3 COLOR, -bg COLOR, -b3 COLOR, --bg3 COLOR
                        Background color of third (contents) column. HTML color name or HEX value. Default is azure.
  -N COLOR, -n COLOR, --num COLOR, --number COLOR, --numbers COLOR
                        Font color of line numbers. HTML color name or HEX value. Default is dimgrey.
