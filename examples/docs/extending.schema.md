---
template: reference
foo: bar
---

# Extending Schema

```
https://example.com/schemas/extending
```

This is an extending schema. It pulls `definitions` from other schemas.

| Abstract | Extensible | Custom Properties | Defined In |
|----------|------------|-------------------|------------|
| Can be instantiated | Yes | Forbidden | [extending.schema.json](extending.schema.json) |

## Schema Hierarchy

* Extending `https://example.com/schemas/extending`
  * [Extensible](extensible.schema.md) `https://example.com/schemas/extensible`
  * [Definitions](definitions.schema.md) `https://example.com/schemas/definitions`

# Extending Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [bar](#bar) | `string` | Optional | [Extensible](extensible.schema.md#bar) |
| [id](#id) | `string` | Optional | [Definitions](definitions.schema.md#id) |
| [baz](#baz) | `string` | Optional | [Extending](#baz) |

## bar

A unique identifier given to every addressable thing.

## id

A unique identifier given to every addressable thing.

## baz
### BAAAZ!

This property has a unique name to demonstrate it&#39;s uniqueness.