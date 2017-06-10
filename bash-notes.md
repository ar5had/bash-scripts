## bash-notes

* [General](http://www.panix.com/~elflord/unix/bash-tute.html)

* [Loop](https://www.cyberciti.biz/faq/bash-for-loop/)

* [if else and other conditionals](http://www.panix.com/~elflord/unix/bash-tute.html)

* [full guide](http://www.tldp.org/LDP/Bash-Beginners-Guide/html/)

* [interestin question on airthmatics](https://unix.stackexchange.com/questions/93029/how-can-i-add-subtract-etc-two-numbers-with-bash)

* [Interesitng question about And/or conditions](http://stackoverflow.com/questions/16203088/bash-if-statement-with-multiple-conditions-throws-an-error)

* `-eq` expects integer operands, use `==` for strings. Bash doesn't float type so use `bc` for such cases.

* [gnu bash manual](https://www.gnu.org/software/bash/manual/bashref.html)

* for not equal operator use `-ne` instead of `-neq`

* learn pipes, subshell and redirection(`>`, `<`, `<<<`, `<<`, `>>`, `>>>`)

* printf in bash

* bc -l gives output max no of decimal values

* scale in bc defaults to 0

* scale variable in bc doesn't do round off

* printf's .nf format specifier does round off digits

* [cut command](http://www.folkstalk.com/2012/02/cut-command-in-unix-linux-examples.html)

* [head, tail, command](http://www.linfo.org/head.html)

* [tr](http://www.thegeekstuff.com/2012/12/linux-tr-command/)

* Difference echo $line b/w echo "$line"-

Double quotes are required to preserve multiple spacing. In absence of that, it replaces sequences of "one or more" blanks with single spaces. That's exactly what's demanded by the problem. Hence, works !

* Difference between `[:space:]` and ` `

* [Sort](https://en.wikipedia.org/wiki/Sort_(Unix))
* [Uniq](http://www.thegeekstuff.com/2013/05/uniq-command-examples/)
* **Note:** `i` parameter findss unique ignoring cases
* [Paste](http://www.theunixschool.com/2012/07/10-examples-of-paste-commanda-usage-in.html)

* [Arrays](http://www.thegeekstuff.com/2010/06/bash-array-tutorial/)

* [awk print examples](http://www.thegeekstuff.com/2010/01/awk-introduction-tutorial-7-awk-print-examples/) [awk if else examples](http://www.thegeekstuff.com/2010/02/awk-conditional-statements/) and [awk afs ors etc](http://www.thegeekstuff.com/2010/01/8-powerful-awk-built-in-variables-fs-ofs-rs-ors-nr-nf-filename-fnr/)