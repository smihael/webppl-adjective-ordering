Code for my master's thesis

# Installation

Make sure you have installed [webppl](http://webppl.org/) along with some other dependencies:

```
npm install -g webppl
mkdir -p ~/.webppl 
npm install --prefix ~/.webppl probmods/webppl-viz
npm install --prefix ~/.webppl mhtess/webppl-bda
npm install --prefix ~/.webppl webppl-csv
```

This package can then be installed using
```
npm install --prefix ~/.webppl smihael/webppl-adjective-ordering
```

# Usage

Separate experiments can be run as follows:

`webppl --require adjective_ordering --require webppl-viz --require webppl-csv  --require webppl-bda basic.wppl`
