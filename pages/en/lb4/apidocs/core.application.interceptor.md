---
lang: en
title: 'API docs: core.application.interceptor'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/core
permalink: /doc/en/lb4/apidocs.core.application.interceptor.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/core](./core.md) &gt; [Application](./core.application.md) &gt; [interceptor](./core.application.interceptor.md)

## Application.interceptor() method

Register an interceptor

<b>Signature:</b>

```typescript
interceptor(interceptor: Interceptor | Constructor<Provider<Interceptor>>, nameOrOptions?: string | InterceptorBindingOptions): Binding<Interceptor>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  interceptor | [Interceptor](./context.interceptor.md) \| [Constructor](./context.constructor.md)<!-- -->&lt;[Provider](./context.provider.md)<!-- -->&lt;[Interceptor](./context.interceptor.md)<!-- -->&gt;&gt; | An interceptor function or provider class |
|  nameOrOptions | string \| [InterceptorBindingOptions](./context.interceptorbindingoptions.md) | Binding name or options |

<b>Returns:</b>

[Binding](./context.binding.md)<!-- -->&lt;[Interceptor](./context.interceptor.md)<!-- -->&gt;

