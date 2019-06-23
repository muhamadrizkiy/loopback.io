---
lang: en
title: 'API docs: repository.defaulthasmanyrepository'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.defaulthasmanyrepository.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [DefaultHasManyRepository](./repository.defaulthasmanyrepository.md)

## DefaultHasManyRepository class

<b>Signature:</b>

```typescript
export declare class DefaultHasManyRepository<TargetEntity extends Entity, TargetID, TargetRepository extends EntityCrudRepository<TargetEntity, TargetID>> implements HasManyRepository<TargetEntity> 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(getTargetRepository, constraint)](./repository.defaulthasmanyrepository._constructor_.md) |  | Constructor of DefaultHasManyEntityCrudRepository |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [constraint](./repository.defaulthasmanyrepository.constraint.md) |  | <code>DataObject&lt;TargetEntity&gt;</code> |  |
|  [getTargetRepository](./repository.defaulthasmanyrepository.gettargetrepository.md) |  | <code>Getter&lt;TargetRepository&gt;</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [create(targetModelData, options)](./repository.defaulthasmanyrepository.create.md) |  |  |
|  [delete(where, options)](./repository.defaulthasmanyrepository.delete.md) |  |  |
|  [find(filter, options)](./repository.defaulthasmanyrepository.find.md) |  |  |
|  [patch(dataObject, where, options)](./repository.defaulthasmanyrepository.patch.md) |  |  |

