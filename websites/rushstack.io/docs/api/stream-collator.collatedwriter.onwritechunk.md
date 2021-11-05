---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/stream-collator](./stream-collator.md) &gt; [CollatedWriter](./stream-collator.collatedwriter.md) &gt; [onWriteChunk](./stream-collator.collatedwriter.onwritechunk.md)

## CollatedWriter.onWriteChunk() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Subclasses should implement this `abstract` method to process the chunk.

<b>Signature:</b>

```typescript
onWriteChunk(chunk: ITerminalChunk): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  chunk | [ITerminalChunk](./terminal.iterminalchunk.md) |  |

<b>Returns:</b>

void
