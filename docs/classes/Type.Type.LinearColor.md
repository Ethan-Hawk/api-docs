[auto-mwapi-lib](../README.md) / [Exports](../modules.md) / [Type](../modules/Type.md) / [Type](../modules/Type.Type.md) / LinearColor

# Class: LinearColor

[Type](../modules/Type.md).[Type](../modules/Type.Type.md).LinearColor

**`Author`**

SuoWei

**`Description`**

线性RGBA颜色

**`Network Status`**

usage:双端

## Table of contents

### Constructors

- [constructor](Type.Type.LinearColor.md#constructor)

### Accessors

- [a](Type.Type.LinearColor.md#a)
- [b](Type.Type.LinearColor.md#b)
- [g](Type.Type.LinearColor.md#g)
- [r](Type.Type.LinearColor.md#r)
- [black](Type.Type.LinearColor.md#black)
- [blue](Type.Type.LinearColor.md#blue)
- [gray](Type.Type.LinearColor.md#gray)
- [green](Type.Type.LinearColor.md#green)
- [red](Type.Type.LinearColor.md#red)
- [white](Type.Type.LinearColor.md#white)
- [yellow](Type.Type.LinearColor.md#yellow)

### Methods

- [addition](Type.Type.LinearColor.md#addition)
- [division](Type.Type.LinearColor.md#division)
- [equality](Type.Type.LinearColor.md#equality)
- [fromString](Type.Type.LinearColor.md#fromstring)
- [inEquality](Type.Type.LinearColor.md#inequality)
- [multiply](Type.Type.LinearColor.md#multiply)
- [subtraction](Type.Type.LinearColor.md#subtraction)
- [toString](Type.Type.LinearColor.md#tostring)
- [colorHexToLinearColor](Type.Type.LinearColor.md#colorhextolinearcolor)
- [colorHsvToLinearColor](Type.Type.LinearColor.md#colorhsvtolinearcolor)
- [colorToLinearColor](Type.Type.LinearColor.md#colortolinearcolor)
- [fromString](Type.Type.LinearColor.md#fromstring-1)
- [makeFromHSV](Type.Type.LinearColor.md#makefromhsv)
- [random](Type.Type.LinearColor.md#random)

## Constructors

### constructor

• **new LinearColor**(`r`, `g`, `b`)

**`Description`**

用给定的 r, g, b 值构建一个新的 Color

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `r` | `number` | usage:r |
| `g` | `number` | usage:g |
| `b` | `number` | usage:b |

#### Defined in

Type/index.d.ts:971

• **new LinearColor**(`r`, `g`, `b`, `a`)

**`Description`**

用给定的 r, g, b ,a 值构建一个新的 Color

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `r` | `number` | usage:r |
| `g` | `number` | usage:g |
| `b` | `number` | usage:b |
| `a` | `number` | usage:a |

#### Defined in

Type/index.d.ts:979

• **new LinearColor**(`v`)

**`Description`**

用给定的 Vector 对象构建一个新的 LinearColor

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | [`Vector`](Type.Type.Vector.md) | usage:Vector 对象 |

#### Defined in

Type/index.d.ts:984

• **new LinearColor**(`c`)

**`Description`**

用给定的 LinearColor 构建一个新的 LinearColor

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `c` | [`LinearColor`](Type.Type.LinearColor.md) | usage:Vector 对象 |

#### Defined in

Type/index.d.ts:989

## Accessors

### a

• `get` **a**(): `number`

**`Description`**

获取当前 LinearColor 的 a 值

#### Returns

`number`

#### Defined in

Type/index.d.ts:1100

• `set` **a**(`v`): `void`

**`Description`**

设置当前 LinearColor 的 a 值

**`Precautions`**

颜色值的有效范围是 0.0 <= value <= 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

Type/index.d.ts:1105

___

### b

• `get` **b**(): `number`

**`Description`**

获取当前 LinearColor 的 b 值

#### Returns

`number`

#### Defined in

Type/index.d.ts:1091

• `set` **b**(`v`): `void`

**`Description`**

设置当前 LinearColor 的 b 值

**`Precautions`**

颜色值的有效范围是 0.0 <= value <= 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

Type/index.d.ts:1096

___

### g

• `get` **g**(): `number`

**`Description`**

获取当前 LinearColor 的 g 值

#### Returns

`number`

#### Defined in

Type/index.d.ts:1082

• `set` **g**(`v`): `void`

**`Description`**

设置当前 LinearColor 的 g 值 颜色值的有效范围是

**`Precautions`**

0.0 <= value <= 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

Type/index.d.ts:1087

___

### r

• `get` **r**(): `number`

**`Description`**

获取当前 LinearColor 的 r 值

#### Returns

`number`

#### Defined in

Type/index.d.ts:1073

• `set` **r**(`v`): `void`

**`Description`**

设置当前 LinearColor 的 r 值

**`Precautions`**

颜色值的有效范围是 0.0 <= value <= 1.0

#### Parameters

| Name | Type |
| :------ | :------ |
| `v` | `number` |

#### Returns

`void`

#### Defined in

Type/index.d.ts:1078

___

### black

• `Static` `get` **black**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

黑色 (0, 0, 0, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1117

___

### blue

• `Static` `get` **blue**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

蓝色 (0, 0, 1, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1129

___

### gray

• `Static` `get` **gray**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

灰色 (0.5, 0.5, 0.5, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1113

___

### green

• `Static` `get` **green**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

绿色 (0, 1, 0, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1125

___

### red

• `Static` `get` **red**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

红色 (1, 0, 0, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1121

___

### white

• `Static` `get` **white**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

白色 (1, 1, 1, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1109

___

### yellow

• `Static` `get` **yellow**(): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

黄色 (1, 1, 0, 1)

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

#### Defined in

Type/index.d.ts:1133

## Methods

### addition

▸ **addition**(`linearColorB`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

颜色值相加

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `linearColorB` | [`LinearColor`](Type.Type.LinearColor.md) | usage:相加的颜色B |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1150

___

### division

▸ **division**(`linearColorB`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

颜色值相除

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `linearColorB` | [`LinearColor`](Type.Type.LinearColor.md) | usage:相除的颜色B |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1177

___

### equality

▸ **equality**(`linearColorB`, `epsilon?`): `boolean`

**`Description`**

判断两个颜色值是否相等

**`Effect`**

调用端生效

**`Precautions`**

相等返回true，不相等返回false

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `linearColorB` | [`LinearColor`](Type.Type.LinearColor.md) | usage:对比的颜色B |
| `epsilon?` | `number` | usage:最小误差数 default:Util.MathUtil.EPSILON |

#### Returns

`boolean`

是否相等

#### Defined in

Type/index.d.ts:1186

___

### fromString

▸ **fromString**(`str`): `void`

**`Description`**

用数据填充对象

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `str` | `string` | usage:数据字符串 |

#### Returns

`void`

#### Defined in

Type/index.d.ts:995

___

### inEquality

▸ **inEquality**(`linearColorB`, `epsilon?`): `boolean`

**`Description`**

判断两个颜色值是否不相等

**`Effect`**

调用端生效

**`Precautions`**

不相等返回true，相等返回false

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `linearColorB` | [`LinearColor`](Type.Type.LinearColor.md) | usage:对比的颜色B |
| `epsilon?` | `number` | usage:最小误差数 default:Util.MathUtil.EPSILON |

#### Returns

`boolean`

是否相等

#### Defined in

Type/index.d.ts:1195

___

### multiply

▸ **multiply**(`linearColorB`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

颜色值相乘

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `linearColorB` | [`LinearColor`](Type.Type.LinearColor.md) | usage:相乘的颜色B |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1168

___

### subtraction

▸ **subtraction**(`linearColorB`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

颜色值相减

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `linearColorB` | [`LinearColor`](Type.Type.LinearColor.md) | usage:相减的颜色B |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1159

___

### toString

▸ **toString**(): `string`

**`Description`**

以字符串的形式输出对象属性

**`Effect`**

调用端生效

#### Returns

`string`

对象属性字符串

#### Defined in

Type/index.d.ts:1008

___

### colorHexToLinearColor

▸ `Static` **colorHexToLinearColor**(`inColorHex`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

将 HexColor 转化为 LinearColor

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `inColorHex` | `string` | usage:HexColor 字符串 |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收转化后的 LinearColor 的对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

LinerColor 对象

#### Defined in

Type/index.d.ts:1034

___

### colorHsvToLinearColor

▸ `Static` **colorHsvToLinearColor**(`h`, `s`, `v`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

将 HsvColor 转化为 LinearColor

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `h` | `number` | usage:色调 |
| `s` | `number` | usage:饱和度 |
| `v` | `number` | usage:明度 |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收转换结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1048

___

### colorToLinearColor

▸ `Static` **colorToLinearColor**(`r`, `g`, `b`, `a?`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

转换 Color

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `r` | `number` | usage:r(0 ~255) |
| `g` | `number` | usage:g(0 ~255) |
| `b` | `number` | usage:b(0 ~255) |
| `a?` | `number` | usage:a(0 ~255) default:255 |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收转换结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1019

___

### fromString

▸ `Static` **fromString**(`jsonStr`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

用数据生成一个新的对象

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonStr` | `string` | usage:数据字符串 |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

新的 LinearColor 类型对象

#### Defined in

Type/index.d.ts:1002

___

### makeFromHSV

▸ `Static` **makeFromHSV**(`h`, `s`, `v`, `outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

将字节色调饱和度亮度转换为 LinearColor

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `h` | `number` | usage:色调 |
| `s` | `number` | usage:饱和度 |
| `v` | `number` | usage:明度 |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收转换结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1064

___

### random

▸ `Static` **random**(`outer?`): [`LinearColor`](Type.Type.LinearColor.md)

**`Description`**

返回具有随机 RGB 值和 Alpha 为 1.0 的新颜色

**`Effect`**

调用端生效

**`Precautions`**

建议传入 outer 来减少 new 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outer?` | [`LinearColor`](Type.Type.LinearColor.md) | usage:接收结果的 LinearColor 对象 default:null |

#### Returns

[`LinearColor`](Type.Type.LinearColor.md)

如果 outer 不为空, 返回 outer, 否则返回一个新的 LinearColor 对象

#### Defined in

Type/index.d.ts:1141
