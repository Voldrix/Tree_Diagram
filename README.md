# Tree Diagram
__A filesystem like tree diagram generator__

Single page, vanilla, no frameworks or dependencies. As simple and minimal as possible.

[Live Demo](https://voldrixia.com/tree/)

### How it works
It takes input like this:
```
my-project
  src
    index.html
    my-project.scss
  build
    index.html
    my-project.css
```
... and transforms it into an ASCII tree diagram like this:

```
.
└── my-project/
    ├── src/
    │   ├── index.html
    │   └── my-project.scss
    └── build/
        ├── index.html
        └── my-project.css
```

### Controls
`Tab` or double space to indent. (It converts tabs to double spaces in the input box)\
Highlight multiple lines + `Tab` to indent them all (two spaces).\
Highlight multiple lines + `Shift` + `Tab` to remove an indent from them all (two spaces).

Partially highlighted lines are included in the shift.

#### Inspiration
I wanted to remake [Nathan Friend](https://gitlab.com/nfriend/tree-online)'s project, but without react and the other tools and dependencies he used.\
To see how little code and how simply it can be done. And as a single page, for easy deployment.

#### License
[MIT](LICENSE)

