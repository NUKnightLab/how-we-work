# Indent style conventions

 * 4 space indents
 * no hard tabs. Set soft tabs in your editor

# brace placement

 * opening brace on end of block starting line
 * closing brace on line by itself
 * closing brace indented to align with block start

e.g.

```
if (someCondition) {
    doSomething();
}
```

# Line length

 * 80 character rule-of-thumb

 In general, try to keep lines around 80 characters or less. We will probably not be as vigilant in Javascript as in Python regarding line length, but a long line should have a pretty good reason.

# Naming conventions

 * camelCase variable names
 * camelCase or PascalCase function names <-- which do we use?

# Commenting

 * [JS Docs](http://usejsdoc.org/)

# function declarations

 * In general, function literal style instead of standard function declarations.

E.g.:

```
var myFunction = function() {
    // do something here
};
```