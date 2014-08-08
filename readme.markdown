This module is like [falafel](https://github.com/substack/node-falafel) with the following differences

- Uses the latest version of Esprima
- Each node has a new method called `oldsource` which gives the source before it was updated using `update`
- Returns undefined if Esprima is unable to parse the string instead of throwing an error.  