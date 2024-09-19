# TextOut
## Search and eXtract text
### Find text inside a file with the ability to locate only columns
just like awk -actually based on it- you can locate the 1st, 2nd, or any order of columns more quickly than GUI tools or even any other tool.
a tool to make it easier and faster to use awk, farther than typing the (poor) advanced syntax every time you use awk, this script is made for u.
## Installing:
### It's a portable script you can locate it in any `$PATH` you prefer, I use `/usr/bin` to make it faster to execute.
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
<hr>
"Don't forget to hit star if you like it..." Beta
