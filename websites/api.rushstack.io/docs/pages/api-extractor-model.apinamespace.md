---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor-model](./api-extractor-model.md) &gt; [ApiNamespace](./api-extractor-model.apinamespace.md)

## ApiNamespace class

Represents a TypeScript namespace declaration.

<b>Signature:</b>

```typescript
export declare class ApiNamespace extends ApiNamespace_base
```

<b>Extends:</b> ApiNamespace_base

## Remarks

This is part of the [ApiModel](./api-extractor-model.apimodel.md) hierarchy of classes, which are serializable representations of API declarations.

`ApiNamespace` represents a TypeScript declaration such `X` or `Y` in this example:

```ts
export namespace X {
  export namespace Y {
    export interface IWidget {
      render(): void;
    }
  }
}
```

## Constructors

| Constructor                                                                   | Modifiers | Description                                                      |
| ----------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------- |
| [(constructor)(options)](./api-extractor-model.apinamespace._constructor_.md) |           | Constructs a new instance of the <code>ApiNamespace</code> class |

## Properties

| Property                                                           | Modifiers | Type                                                | Description |
| ------------------------------------------------------------------ | --------- | --------------------------------------------------- | ----------- |
| [containerKey](./api-extractor-model.apinamespace.containerkey.md) |           | string                                              |             |
| [kind](./api-extractor-model.apinamespace.kind.md)                 |           | [ApiItemKind](./api-extractor-model.apiitemkind.md) |             |

## Methods

| Method                                                                                     | Modifiers           | Description          |
| ------------------------------------------------------------------------------------------ | ------------------- | -------------------- |
| [buildCanonicalReference()](./api-extractor-model.apinamespace.buildcanonicalreference.md) |                     | <b><i>(BETA)</i></b> |
| [getContainerKey(name)](./api-extractor-model.apinamespace.getcontainerkey.md)             | <code>static</code> |                      |