# Code Style Guide
A coding style guide for Denver Post newsroom projects

## Spaces vs. tabs
Spaces. Four of 'em.

## Naming conventions

### File names
Preferrably all lower case, hyphens instead of underscores.

### Directory names
Preferrably all lower case, hyphens instead of underscores.

### Variable names
In general, under_scores are preferred to camelCase. Some languages vary.

### Function / method and class names

## Directory structure

## HTML
Markup should [validate](https://validator.w3.org/). Avoid `<div>`'s and `<br>`'s in the favor of semantic elements.

## JS
Create objects whenever possible. Free-floating functions and variables are the devil's work.

## CSS

## PHP

### Braces vs. endif/endfor
`{`'s and `}`'s get unwieldy quickly. Use explicit open and close statments instead, ala:

```php
if ( somecondition ):
    someexecution;
endif```

Note: If writing WordPress PHP, adhere to [WordPress coding standards](https://codex.wordpress.org/WordPress_Coding_Standards)

## Python
