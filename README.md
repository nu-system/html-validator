# html-validator

Semantic HTML linter in just pure CSS way.

## How to start

```
npm i @_nu/html-validator
```

Or just add the tag below in your html page

```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@_nu/html-validator" />
```

If you just wanna use level1 try 

```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@_nu/html-validator/level1.css" />
```

## Content

```bash
html-validator/css
├── level1.css    // leve1 「 red 」:  force validate rules
└── level2.css    // leve2 「 yellow 」: level1.css + suggest validate rules
```

All valid msg on css prop of `content`.

## Prior art

html-lint was build on this awesome projects:

* https://github.com/t7/construct.css
