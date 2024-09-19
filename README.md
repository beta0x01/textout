# TextOut
## Search and eXtract text
### Find text inside a file with the ability to locate with columns
just like AWK -actually based on it- you can locate the 1st, 2nd, or any order of columns more quickly than GUI tools or even any other tool.
a tool to make it easier and faster to use AWK, farther than typing the (poor) advanced syntax every time you use AWK, this script is made for u.
## Installing:
### Make sure to make it executable first by `chmod +x textout`
It's a portable script you can locate it in any `$PATH` you prefer, I use `/usr/bin` to make it faster to execute.
#### OR just and w/o headeche use `./textout -h` if you prefer
## Usage: 
`textout -h` Here you will find everything.
## Examples
### Basic
`textout -f http-urls.txt -s '://' -c 2 -o just-domains.txt`
### Sort
`textout -r -f http-urls.txt -s '://' -c 2 -o just-domains.txt`
### Version
`textout -v`
### Help Menu
`textout -h`
#### It's OpenSource script, so conributions are available and very welcome, issues YOU_MAKE_IT_RUN...
#### "Don't forget to hit star if you like it..." Beta
