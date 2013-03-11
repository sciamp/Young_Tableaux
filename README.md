get the code:
git clone git://github.com/sciamp/sandbox.git

add sandbox path to maxima load path:
file_search_maxima : append (file_search_maxima, ["~/your/path/to/sandbox/"]);

load young:
load ("young.mac");