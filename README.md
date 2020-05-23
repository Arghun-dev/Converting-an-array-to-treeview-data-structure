# Converting-an-array-to-treeview-data-structure

For example we want to convert an array like this:

```
resultBody: [
  {
    .
    .
    .
  },
  {
    .
    .
    .
  }
]
```

To:

```
resultBody: {
  items: [
    {
      .
      .
      .
    },
    {
      .
      .
      .
    }
  ]
}
```

DO THIS:

```
const resultBodyToObject = { items: [...this.props.resultBody] }
```
