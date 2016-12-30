TODO: [![Build Status](https://travis-ci.org/marcus7777/lunr-js.svg?branch=master)](https://travis-ci.org/marcus7777/lunr-js)
# elasticlunr-js

##A Polymer filter using [elasticlunr.js](https://github.com/weixsong/elasticlunr.js) for a Array of Objects with common properties.

To use 
```
<elasticlunr-js
  data="[[data]]"
  search="{{search}}"
  output="{{output}}" >
</elasticlunr-js>
```
more
```
<elasticlunr-js
  data="[[data]]"
  search="{{search}}"
  output="{{output}}"
  fields="['name','tags']"
  limit=30
  minScore=.5
  >
</elasticlunr-js>
```
Needed

```data``` : An Array of Objects with common properties.

```search``` : Search term.

```output``` : The Searched Array.

Options
TODO: Some differences in lunr and elasticlunr. Review API for these optional fields.

```fields``` : Fields to search

```limit```: Limit results

```minScore```: From 0 to 1 

```log```: if you are seeing what's happening
