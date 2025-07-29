[**@hydroperx/color**](../README.md)

***

[@hydroperx/color](../globals.md) / Color

# Interface: Color

Defined in: [Color.ts:19](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L19)

## Methods

### alpha()

#### Call Signature

> **alpha**(): `number`

Defined in: [Color.ts:20](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L20)

##### Returns

`number`

#### Call Signature

> **alpha**(`val`): `Color`

Defined in: [Color.ts:21](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L21)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### array()

> **array**(): `number`[]

Defined in: [Color.ts:84](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L84)

#### Returns

`number`[]

***

### black()

#### Call Signature

> **black**(): `number`

Defined in: [Color.ts:53](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L53)

##### Returns

`number`

#### Call Signature

> **black**(`val`): `Color`

Defined in: [Color.ts:54](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L54)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### blacken()

> **blacken**(`ratio`): `Color`

Defined in: [Color.ts:68](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L68)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### blue()

#### Call Signature

> **blue**(): `number`

Defined in: [Color.ts:29](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L29)

##### Returns

`number`

#### Call Signature

> **blue**(`val`): `Color`

Defined in: [Color.ts:30](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L30)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### contrast()

> **contrast**(`other`): `number`

Defined in: [Color.ts:57](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L57)

#### Parameters

##### other

`Color`

#### Returns

`number`

***

### cyan()

#### Call Signature

> **cyan**(): `number`

Defined in: [Color.ts:44](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L44)

##### Returns

`number`

#### Call Signature

> **cyan**(`val`): `Color`

Defined in: [Color.ts:45](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L45)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### darken()

> **darken**(`ratio`): `Color`

Defined in: [Color.ts:63](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L63)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### delta()

> **delta**(`other`): `number`

Defined in: [Color.ts:78](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L78)

Returns the percent (`[0, 100]`) of difference between two colors
using the deltaE algorithm.

#### Parameters

##### other

`Color`

#### Returns

`number`

***

### desaturate()

> **desaturate**(`ratio`): `Color`

Defined in: [Color.ts:65](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L65)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### fade()

> **fade**(`ratio`): `Color`

Defined in: [Color.ts:69](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L69)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### grayscale()

> **grayscale**(): `Color`

Defined in: [Color.ts:66](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L66)

#### Returns

`Color`

***

### green()

#### Call Signature

> **green**(): `number`

Defined in: [Color.ts:26](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L26)

##### Returns

`number`

#### Call Signature

> **green**(`val`): `Color`

Defined in: [Color.ts:27](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L27)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### hex()

> **hex**(): `string`

Defined in: [Color.ts:86](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L86)

#### Returns

`string`

***

### hexa()

> **hexa**(): `string`

Defined in: [Color.ts:87](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L87)

#### Returns

`string`

***

### hsl()

> **hsl**(...`rest`): `Color`

Defined in: [Color.ts:81](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L81)

#### Parameters

##### rest

...`number`[]

#### Returns

`Color`

***

### hsv()

> **hsv**(...`rest`): `Color`

Defined in: [Color.ts:82](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L82)

#### Parameters

##### rest

...`number`[]

#### Returns

`Color`

***

### hue()

#### Call Signature

> **hue**(): `number`

Defined in: [Color.ts:32](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L32)

##### Returns

`number`

#### Call Signature

> **hue**(`val`): `Color`

Defined in: [Color.ts:33](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L33)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### isDark()

> **isDark**(): `boolean`

Defined in: [Color.ts:59](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L59)

#### Returns

`boolean`

***

### isLight()

> **isLight**(): `boolean`

Defined in: [Color.ts:58](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L58)

#### Returns

`boolean`

***

### lab()

> **lab**(...`rest`): `Color`

Defined in: [Color.ts:83](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L83)

#### Parameters

##### rest

...`number`[]

#### Returns

`Color`

***

### lighten()

> **lighten**(`ratio`): `Color`

Defined in: [Color.ts:62](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L62)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### lightness()

#### Call Signature

> **lightness**(): `number`

Defined in: [Color.ts:41](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L41)

##### Returns

`number`

#### Call Signature

> **lightness**(`val`): `Color`

Defined in: [Color.ts:42](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L42)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### luminosity()

> **luminosity**(): `number`

Defined in: [Color.ts:56](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L56)

#### Returns

`number`

***

### magenta()

#### Call Signature

> **magenta**(): `number`

Defined in: [Color.ts:47](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L47)

##### Returns

`number`

#### Call Signature

> **magenta**(`val`): `Color`

Defined in: [Color.ts:48](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L48)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### mix()

> **mix**(`other`, `ratio?`): `Color`

Defined in: [Color.ts:72](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L72)

#### Parameters

##### other

`Color`

##### ratio?

`number`

#### Returns

`Color`

***

### negate()

> **negate**(): `Color`

Defined in: [Color.ts:61](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L61)

#### Returns

`Color`

***

### opaquer()

> **opaquer**(`ratio`): `Color`

Defined in: [Color.ts:70](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L70)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### red()

#### Call Signature

> **red**(): `number`

Defined in: [Color.ts:23](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L23)

##### Returns

`number`

#### Call Signature

> **red**(`val`): `Color`

Defined in: [Color.ts:24](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L24)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### rgb()

> **rgb**(...`rest`): `Color`

Defined in: [Color.ts:80](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L80)

#### Parameters

##### rest

...`number`[]

#### Returns

`Color`

***

### rgbNumber()

> **rgbNumber**(): `number`

Defined in: [Color.ts:85](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L85)

#### Returns

`number`

***

### rotate()

> **rotate**(`degrees`): `Color`

Defined in: [Color.ts:71](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L71)

#### Parameters

##### degrees

`number`

#### Returns

`Color`

***

### saturate()

> **saturate**(`ratio`): `Color`

Defined in: [Color.ts:64](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L64)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### saturationl()

#### Call Signature

> **saturationl**(): `number`

Defined in: [Color.ts:35](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L35)

##### Returns

`number`

#### Call Signature

> **saturationl**(`val`): `Color`

Defined in: [Color.ts:36](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L36)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### saturationv()

#### Call Signature

> **saturationv**(): `number`

Defined in: [Color.ts:38](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L38)

##### Returns

`number`

#### Call Signature

> **saturationv**(`val`): `Color`

Defined in: [Color.ts:39](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L39)

##### Parameters

###### val

`number`

##### Returns

`Color`

***

### string()

> **string**(): `string`

Defined in: [Color.ts:88](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L88)

#### Returns

`string`

***

### whiten()

> **whiten**(`ratio`): `Color`

Defined in: [Color.ts:67](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L67)

#### Parameters

##### ratio

`number`

#### Returns

`Color`

***

### yellow()

#### Call Signature

> **yellow**(): `number`

Defined in: [Color.ts:50](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L50)

##### Returns

`number`

#### Call Signature

> **yellow**(`val`): `Color`

Defined in: [Color.ts:51](https://github.com/hydroperx/color.js/blob/f5652430259af52de94b4f72a733f0f0e97967f2/src/Color.ts#L51)

##### Parameters

###### val

`number`

##### Returns

`Color`
