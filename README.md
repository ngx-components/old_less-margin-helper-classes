[![AngularJS Express](http://i.imgur.com/nTj9QgN.png)](https://github.com/angular-express/angular-express)

## LESS margin helper classes

Set of LESS margin helper classes that allow you to quickly assign various levels of margin to elements using plain CSS classes.

## Installation

To install the component:

```bash
$ ngx install less-margin-helper-classes
```

No clue what the `ngx` command line tool is? Learn more about [AngularJS Express](https://github.com/angular-express/angular-express).

## How to use

The components exposes the following CSS classes:

```less
@margin-xxs: .1rem;
@margin-xs: .3rem;
@margin-s: .5rem;
@margin-m: 1rem;
@margin-l: 1.5rem;
@margin-xl: 3rem;
@margin-xxl: 6rem;

.margin-xxs{ margin: @margin-xxs; }
.margin-top-xxs{ margin-top: @margin-xxs; }
.margin-right-xxs{ margin-right: @margin-xxs; }
.margin-bottom-xxs{ margin-bottom: @margin-xxs; }
.margin-left-xxs{ margin-left: @margin-xxs; }

.margin-xs{ margin: @margin-xs; }
.margin-top-xs{ margin-top: @margin-xs; }
.margin-right-xs{ margin-right: @margin-xs; }
.margin-bottom-xs{ margin-bottom: @margin-xs; }
.margin-left-xs{ margin-left: @margin-xs; }

.margin-s{ margin: @margin-s; }
.margin-top-s{ margin-top: @margin-s; }
.margin-right-s{ margin-right: @margin-s; }
.margin-bottom-s{ margin-bottom: @margin-s; }
.margin-left-s{ margin-left: @margin-s; }

.margin-m{ margin: @margin-m; }
.margin-top-m{ margin-top: @margin-m; }
.margin-right-m{ margin-right: @margin-m; }
.margin-bottom-m{ margin-bottom: @margin-m; }
.margin-left-m{ margin-left: @margin-m; }

.margin-l{ margin: @margin-l; }
.margin-top-l{ margin-top: @margin-l; }
.margin-right-l{ margin-right: @margin-l; }
.margin-bottom-l{ margin-bottom: @margin-l; }
.margin-left-l{ margin-left: @margin-l; }

.margin-xl{ margin: @margin-xl; }
.margin-top-xl{ margin-top: @margin-xl; }
.margin-right-xl{ margin-right: @margin-xl; }
.margin-bottom-xl{ margin-bottom: @margin-xl; }
.margin-left-xl{ margin-left: @margin-xl; }

.margin-xxl{ margin: @margin-xxl; }
.margin-top-xxl{ margin-top: @margin-xxl; }
.margin-right-xxl{ margin-right: @margin-xxl; }
.margin-bottom-xxl{ margin-bottom: @margin-xxl; }
.margin-left-xxl{ margin-left: @margin-xxl; }
```

The variables can be adjusted to tweak the different sizes.

## License

MIT.
