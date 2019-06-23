---
lang: en
title: 'API docs: repository.fields'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.fields.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [Fields](./repository.fields.md)

## Fields type

Selection of fields

Example: `{afieldname: true}`

<b>Signature:</b>

```typescript
export declare type Fields<MT = AnyObject> = {
    [P in keyof MT]?: boolean;
};
```
