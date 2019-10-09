# mac-digraph
Replacement rules for Mac OS to input digraph as in vim.
This is a neat way to input unicode characters. 
While not as nice as latex one can use it to type math symbols or add a few foreign characters. 
Or potentially other special characters. 
The way of searching the character in the symbols of a font is tedious.

The idea is to allow input of digraphs such as in vim inside any OSX app.
I chose the `§` as marker so to input as it is conveniently in the upper left of my keyboard and I rarely use the symbol.



## Installation 

Drag the digraph.plist onto the text replacement list. 
[See also.](https://support.apple.com/en-us/HT204006)
Note the digraph list includes over 1200 replacements.

To uninstall mark all the replacements and press the minus button.

## List of Digraphs

A full list of digraphs is at the bottom of this [vim documentation](https://vimhelp.org/digraph.txt.html).
Note: some are unprintable and were not mapped.



## Some examples

 - `№` one would need to type `§N0`
 - `∃` would be input as `§TE`
 - `∀` would be input as `§FA`
 - `√` would be input as `§RT`
 - `⅓` would be input as `§13`
 - `ⅷ` would be input as `§8r`
 - `Ⅷ` would be input as `§8R`
 - `モ` would be input as `§Mo`
 - `Д` would be input as `§D=`
 - `ץ` input `§Zj`
