---
title: AudioCurve
---

## Summary

### Constructors

|  |
| --- |
| **[AudioCurve](#constructor-0)**() |
| **[AudioCurve](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "points" >}} | [AudioCurvePoint](/vext/ref/fb/audiocurvepoint)[] |
| {{< prop "curveType" >}} | [AudioCurveType](/vext/ref/fb/audiocurvetype) |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [AudioCurve](/vext/ref/fb/audiocurve) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "AudioCurve" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### AudioCurve {#constructor-0}

> **AudioCurve**()

Creates a new [AudioCurve](/vext/ref/fb/audiocurve) frostbite instance.

### AudioCurve {#constructor-1}

> **AudioCurve**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [AudioCurve](/vext/ref/fb/audiocurve) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "points" %}}

> **[AudioCurvePoint](/vext/ref/fb/audiocurvepoint)**[]

### {{% prop-heading "curveType" %}}

> **[AudioCurveType](/vext/ref/fb/audiocurvetype)**

## Methods

### Clone {#clone}

> **Clone**(): [AudioCurve](/vext/ref/fb/audiocurve)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[AudioCurve](/vext/ref/fb/audiocurve)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [AudioCurve](/vext/ref/fb/audiocurve) type.

