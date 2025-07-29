[**@hydroperx/color**](../README.md)

***

[@hydroperx/color](../globals.md) / ColorObserver

# Class: ColorObserver

Defined in: [ColorObserver.ts:9](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/ColorObserver.ts#L9)

Detects character color used in an element.

Make sure to use this class under an `useEffect` hook (using `[]` (empty) dependencies)
and on cleanup, invoke `ColorObserver#cleanup()`.

## Constructors

### Constructor

> **new ColorObserver**(`element`, `callback`): `ColorObserver`

Defined in: [ColorObserver.ts:14](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/ColorObserver.ts#L14)

#### Parameters

##### element

`null` | `HTMLElement`

##### callback

(`color`) => `void`

#### Returns

`ColorObserver`

## Methods

### cleanup()

> **cleanup**(): `void`

Defined in: [ColorObserver.ts:39](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/ColorObserver.ts#L39)

#### Returns

`void`
