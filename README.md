# atom-lambda-decorator
Decorate your lambda (anonymous) functions with the λ character.

![Preview](http://i.imgur.com/tUseVXl.png)

### Things that will be decorated:
 - `() => {}` - Fat-arrow functions with parentheses for arugments and curly braces for body
 - `() => x` - Fat-arrow functions with parentheses for arguments and a return value for body
 - `x => x` - Fat-arrow functions with raw single argument and a return value for body
 - `function() {}` - Old-school ES5 anonymous functions
 
### Things that will not be decorated:
 - `function namedFn() {}` - Named functions
 - `class xyz {}` - Classes

## Usage
Paste the contents of [`styles.less`](https://github.com/wyqydsyq/atom-lambda-decorator/blob/master/styles.less) into your `stylesheet.less` (From `Edit` → `Stylesheet...` in Atom) and enjoy!

## Backstory
I've recently started using [Fira Code](https://github.com/tonsky/FiraCode) in Atom and have been loving the ligatures which made me wonder if there's any other kind of decoration I could do on my code to aid in readability. I thought a decorator for lambda functions would be kind of nifty so here we are.
