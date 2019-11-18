# html-validator

Help linter for semantic HTML in just pure CSS way.

Base on the [validator.w3.org](https://validator.w3.org/)

## How to start

```
npm i @_nu/html-validator
```

Or just add the tag below in your html page

```HTML
<link rel="stylesheet" src="https://cdn.jsdelivr.net/npm/@_nu/html-validator/css/validator.css" />
```

2 kinds of validator:
1. Add `:before` of the invalid element
2. Outline of the invalid element

Both of them can find the valid msg on css prop of `content`.

3 kinds of validate level:
1. red: have to fixed
2. yellow: suggest to fixed
3. blue: some tips for this rule


## Prior art

html-lint was build on this awesome projects:

* https://github.com/t7/construct.css
