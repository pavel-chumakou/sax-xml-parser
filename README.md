# SAX XML Parser

Simple XML-aware parser written in [B](https://github.com/bext-lang/b) language.

## Build
```bash
./build/b -q  sax-xml-parser.b
```
## Usage
    Usage: sax-xml-parser [OPTIONS] <input...>
    OPTIONS:
        -f <file>
            Parse content of a file
        -s "<str>"
            Parse input string
        -e  
            Parse example string: <!DOCTYPE html><html><body><h1>My Heading</h1><p>My paragraph</p></body></html>
        -t <file>
            Extract text from a XML(HTML) file

