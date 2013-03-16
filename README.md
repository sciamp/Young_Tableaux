get the code:
git clone git://github.com/sciamp/sandbox.git

add sandbox path to maxima load path:
file_search_maxima : cons(sconcat("/path/to/this/directory/###.{lisp,mac,mc}"), file_search_maxima);

load young:
load (young);