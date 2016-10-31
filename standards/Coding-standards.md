## TL;DR

A quick summary of our code style for the impatient

### All languages

   * 4-space, soft-tab indents
   * 80-character line lengths where practical
   * no trailing whitespace
   * blank lines between major blocks (functions, modules, classes) but not generally within them
   * naming:
     - prefer words to abbreviations to single letters. Exceptions for "throw-away" variables (e.g. i,j loops)
     - only begin with lowercase letters or _, except for class names
     - TODO: How to handle acronyms like HTML, PDF, URL ?

### Python

   * PEP8
   * naming
     - snake_case variables, functions, and methods
     - PascalCase classes
     - avoid name-mangled dunder privates. In general, use dunders only for conventional and language-specific cases (__init__, __pycache__, etc.)

### Javascript

   * 1TBS brace styling 
     - `{` goes on end of block def line
     - `}` on own line, aligned with block
     - Don't skimp on braces for single-line statements
     - cuddle else
     - space before brace
   * naming
     - camelCase functions and variables
     - PascalCase functions (?) and classes (um?) # TODO: this needs attention

# KnightLab Coding Standards

## Language-specific guidelines

 * [Python](https://github.com/NUKnightLab/how-we-work/blob/master/standards/Coding-standards:-Python.md)
 * [Javascript](https://github.com/NUKnightLab/how-we-work/blob/master/standards/Coding-standards:-Javascript.md)

## Categories of concern

 * Indent style conventions
 * spaces or tabs. Use soft tabs
 * brace placement
 * Line length conventions
 * Naming conventions

## General principles

 * Defer to community coding standards when possible
 * use [EditorConfig](http://editorconfig.org/) where possible
 * practice a general code review process
 * avoid premature optimization
 * maintain clarity about scoping, encapsulation, and general separation of concerns
 * keep code blocks readable and cohesive
 * clarity over cleverness

## Rules of thumb

 * functions about 20 lines max
 * lines about 80 characters max
 * code reviews/PRs in the 100 to 300 line range

## Comments on Commenting

 * Write block-level comments for modules, functions, and classes
   - consider documenting blocks before writing the code to be sure your intentions are clear
   - Use JS Doc for javascript block-level docs
 * As much as possible, the code is the comment. The primary exception is block-level comments
 * If you are over-commenting or code is not understandable w/o extensive comments:
   - re-evaulate variable and function names
   - refactor to more focused, cohesive code blocks
 * Keep comments accurate. Outdated comments are crazy-making

## Programming practices

 * Git - when to branch, commit, pull request
 * commit messages - utilize # and @
 * Rebase vs Merging. Do we want merge commits? 
 * Squashing commits and making sure commits are tied to features, bugs etc

## Resources/References

### Multi-language/language independent

 * (MOZ) [Mozilla Code conventions](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Coding_Style)
Not definitive, but can be used as a broader reference if needed. They get some things wrong. The brace style they define is not K&R as stated. It is 1TBS, which is what we will be using

### Javascript

 * (Crockford) Douglas Crockford's [Code Conventions for the JavaScript Programming Language] (http://javascript.crockford.com/code.html)
 * (GJS) [Google Javascript Style Guide](https://google.github.io/styleguide/javascriptguide.xml)
Comment docs. JS Docs: http://usejsdoc.org/
 * (JSDOC) [http://usejsdoc.org/]

### Python

 * (PEP8) [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
 * (PEP20) [PEP 20 -- the Zen of Python](https://www.python.org/dev/peps/pep-0020/)
 * (Goodger) [David Goodger's Code like a Pythonista: Idiomatic Python](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)
 * (Reitz) [Kenneth Reitz's The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/)

### CSS/Sass (We need to pick one)

 * (OOCSS) [Object-Oriented CSS](https://github.com/stubbornella/oocss/wiki)
 * (BEM) [BEM](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)
 * (SMACSS) [SMACSS](https://smacss.com/) 





