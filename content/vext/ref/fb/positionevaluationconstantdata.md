---
title: PositionEvaluationConstantData
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[PositionEvaluationConstantData](#constructor-0)**() |
| **[PositionEvaluationConstantData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[PositionEvaluationConstantData](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[PositionEvaluationConstantData](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "ownRandomPositionsRadius" >}} | float |
| {{< prop "leaderRandomPositionsRadius" >}} | float |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "PositionEvaluationConstantData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### PositionEvaluationConstantData {#constructor-0}

> **PositionEvaluationConstantData**()

Creates a new [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata) frostbite instance.

### PositionEvaluationConstantData {#constructor-1}

> **PositionEvaluationConstantData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### PositionEvaluationConstantData {#constructor-2}

> **PositionEvaluationConstantData**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata). |

### PositionEvaluationConstantData {#constructor-3}

> **PositionEvaluationConstantData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata). |

## Properties

### {{% prop-heading "ownRandomPositionsRadius" %}}

> **float**

### {{% prop-heading "leaderRandomPositionsRadius" %}}

> **float**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [PositionEvaluationConstantData](/vext/ref/fb/positionevaluationconstantdata) type.

