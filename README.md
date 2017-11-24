# oxford_3000
The Oxford English Dictionary's basic three thousand words, as a JSON

There seem to actually be 3,847 words here `shrug`

Originally sourced from [Oliver Collins' list](https://github.com/OliverCollins/Oxford-3000-Word-List/blob/master/Oxford%203000%20Word%20List.txt)

## How do I use this?

Simple as pie.

To install, just like any ol' module:

```
npm install --save-dev oxford_3000
```

To use, from a Node REPL, just like any ol' module:

```
> const ox = require('oxford_3000');
undefined

> ox.length;
3847

> ox[2];
'abandoned'
```

`require`ing the module simply resolves to a flat array of strings, of the form

```
[ "a", "abandon", "abandoned", "ability", "able", ... ]
```