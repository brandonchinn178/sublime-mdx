---
a: 1
b: [1, asdf, true]
c:
  a:
    b: asdf
---

# A heading

This is an *example* with [markdown formatting](https://example.com).

```python
def foo(a, b):
    return a + b
```

import Component from 'my-library'

This is some more text with an inline <Component /> *tag*.

export * from './sublibrary'

<Component>A **formatted** text</Component>

<Component str={asdf() + 'asdf'}>
    Some [text](https://example.com) *with formatting*
</Component>

<Component click={() => console.log(true)} />

More **text**.

## A subheading with <Component /> and {name.toString()}

<Component bool={1 > 2} />
