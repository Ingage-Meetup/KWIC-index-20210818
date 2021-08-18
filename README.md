# KWIC Index

## Description

A Key Word in Context (KWIC) index system accepts as input an ordered set of lines, each line is an ordered set of words, and each word is an ordered set of characters. 

Any line may be “circularly shifted” by repeatedly removing the first word and appending it at the end of the line. 

The KWIC index system outputs a listing of all circular shifts of all lines in alphabetical order of the keyword used to shift the line.

Note: Common (stop) words may be omitted!

## Example

Original title – *Gone with the Wind* 

* Circular shifts (key words underlined) 

  * Gone with the Wind 

  * with the Wind Gone 

  * the Wind Gone with 

  * Wind Gone with the 

* Stop word removal 

  * Gone with the Wind 

  * Wind Gone with the

