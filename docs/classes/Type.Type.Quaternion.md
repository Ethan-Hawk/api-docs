[auto-mwapi-lib](../README.md) / [Exports](../modules.md) / [Type](../modules/Type.md) / [Type](../modules/Type.Type.md) / Quaternion

# Class: Quaternion

[Type](../modules/Type.md).[Type](../modules/Type.Type.md).Quaternion

**`Author`**

SuoWei

**`Description`**

四元数

**`Network Status`**

usage:双端

## Table of contents

### Constructors

- [constructor](Type.Type.Quaternion.md#constructor)

### Properties

- [w](Type.Type.Quaternion.md#w)
- [x](Type.Type.Quaternion.md#x)
- [y](Type.Type.Quaternion.md#y)
- [z](Type.Type.Quaternion.md#z)
- [halfToRad](Type.Type.Quaternion.md#halftorad)

### Accessors

- [conjugated](Type.Type.Quaternion.md#conjugated)
- [inverted](Type.Type.Quaternion.md#inverted)
- [length](Type.Type.Quaternion.md#length)
- [normalized](Type.Type.Quaternion.md#normalized)
- [sqrLength](Type.Type.Quaternion.md#sqrlength)
- [identity](Type.Type.Quaternion.md#identity)

### Methods

- [clone](Type.Type.Quaternion.md#clone)
- [equals](Type.Type.Quaternion.md#equals)
- [fromRotation](Type.Type.Quaternion.md#fromrotation)
- [getAxisX](Type.Type.Quaternion.md#getaxisx)
- [getAxisY](Type.Type.Quaternion.md#getaxisy)
- [getAxisZ](Type.Type.Quaternion.md#getaxisz)
- [getEuler](Type.Type.Quaternion.md#geteuler)
- [getEulerAngles](Type.Type.Quaternion.md#geteulerangles)
- [normalize](Type.Type.Quaternion.md#normalize)
- [set](Type.Type.Quaternion.md#set)
- [setEulerAngles](Type.Type.Quaternion.md#seteulerangles)
- [strictEquals](Type.Type.Quaternion.md#strictequals)
- [toRotation](Type.Type.Quaternion.md#torotation)
- [toString](Type.Type.Quaternion.md#tostring)
- [calculateW](Type.Type.Quaternion.md#calculatew)
- [conjugate](Type.Type.Quaternion.md#conjugate)
- [dot](Type.Type.Quaternion.md#dot)
- [equals](Type.Type.Quaternion.md#equals-1)
- [fromAngleZ](Type.Type.Quaternion.md#fromanglez)
- [fromAxes](Type.Type.Quaternion.md#fromaxes)
- [fromAxisAngle](Type.Type.Quaternion.md#fromaxisangle)
- [fromMatrix3x3](Type.Type.Quaternion.md#frommatrix3x3)
- [fromRotation](Type.Type.Quaternion.md#fromrotation-1)
- [fromViewUp](Type.Type.Quaternion.md#fromviewup)
- [getAxis](Type.Type.Quaternion.md#getaxis)
- [getAxisAngle](Type.Type.Quaternion.md#getaxisangle)
- [invert](Type.Type.Quaternion.md#invert)
- [lerp](Type.Type.Quaternion.md#lerp)
- [multiply](Type.Type.Quaternion.md#multiply)
- [multiplyVector](Type.Type.Quaternion.md#multiplyvector)
- [normalize](Type.Type.Quaternion.md#normalize-1)
- [rotateAround](Type.Type.Quaternion.md#rotatearound)
- [rotateAroundLocal](Type.Type.Quaternion.md#rotatearoundlocal)
- [rotateX](Type.Type.Quaternion.md#rotatex)
- [rotateY](Type.Type.Quaternion.md#rotatey)
- [rotateZ](Type.Type.Quaternion.md#rotatez)
- [rotationTo](Type.Type.Quaternion.md#rotationto)
- [slerp](Type.Type.Quaternion.md#slerp)
- [sqlerp](Type.Type.Quaternion.md#sqlerp)
- [strictEquals](Type.Type.Quaternion.md#strictequals-1)
- [toMatrix3x3](Type.Type.Quaternion.md#tomatrix3x3)

## Constructors

### constructor

• **new Quaternion**(`v`)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元素 |

#### Defined in

Type/index.d.ts:2323

• **new Quaternion**(`x?`, `y?`, `z?`, `w?`)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x?` | `number` | usage:x分量 default:0 |
| `y?` | `number` | usage:y分量 default:0 |
| `z?` | `number` | usage:z分量 default:0 |
| `w?` | `number` | usage:w分量 default:1 |

#### Defined in

Type/index.d.ts:2330

## Properties

### w

• **w**: `number`

**`Description`**

w 分量。

#### Defined in

Type/index.d.ts:2319

___

### x

• **x**: `number`

**`Description`**

x 分量。

#### Defined in

Type/index.d.ts:2307

___

### y

• **y**: `number`

**`Description`**

y 分量。

#### Defined in

Type/index.d.ts:2311

___

### z

• **z**: `number`

**`Description`**

z 分量。

#### Defined in

Type/index.d.ts:2315

___

### halfToRad

▪ `Static` `Private` **halfToRad**: `any`

**`Description`**

获取一个半弧度系数

#### Defined in

Type/index.d.ts:1993

## Accessors

### conjugated

• `get` **conjugated**(): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

返回当前四元数的共轭四元数，对单位四元数与求逆等价，但更高效

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

#### Defined in

Type/index.d.ts:2400

___

### inverted

• `get` **inverted**(): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

返回当前四元数的逆

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

#### Defined in

Type/index.d.ts:2396

___

### length

• `get` **length**(): `number`

**`Description`**

求四元数长度

#### Returns

`number`

#### Defined in

Type/index.d.ts:2388

___

### normalized

• `get` **normalized**(): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

返回一个当前四元数归一后的新四元数

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

#### Defined in

Type/index.d.ts:2384

___

### sqrLength

• `get` **sqrLength**(): `number`

**`Description`**

求四元数长度平方

#### Returns

`number`

#### Defined in

Type/index.d.ts:2392

___

### identity

• `Static` `get` **identity**(): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

获取一个单位四元数

**`Precautions`**

Quaternion(0,0,0,1)

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

#### Defined in

Type/index.d.ts:1998

## Methods

### clone

▸ **clone**(): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

克隆当前四元数。

**`Effect`**

调用端生效

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

四元数

#### Defined in

Type/index.d.ts:2336

___

### equals

▸ **equals**(`other`, `epsilon?`): `boolean`

**`Description`**

判断当前四元数是否在误差范围内与指定向量相等。

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Quaternion`](Type.Type.Quaternion.md) | usage:比对的目标四元数 |
| `epsilon?` | `number` | usage:容差值 default:MathDefine.EPSILON |

#### Returns

`boolean`

比对后的结果

#### Defined in

Type/index.d.ts:2373

___

### fromRotation

▸ **fromRotation**(`v`): `void`

**`Description`**

当前四元数读取一个旋转数据

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | [`Rotation`](Type.Type.Rotation.md) | usage:读取的旋转数据 |

#### Returns

`void`

#### Defined in

Type/index.d.ts:2444

___

### getAxisX

▸ **getAxisX**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

返回定义此四元数的坐标系 X 轴向量

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收结果的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

此四元数的坐标系 X 轴向量

#### Defined in

Type/index.d.ts:2413

___

### getAxisY

▸ **getAxisY**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

返回定义此四元数的坐标系 Y 轴向量

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收结果的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

此四元数的坐标系 Y 轴向量

#### Defined in

Type/index.d.ts:2421

___

### getAxisZ

▸ **getAxisZ**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

返回定义此四元数的坐标系 Z 轴向量

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收结果的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

此四元数的坐标系 Z 轴向量

#### Defined in

Type/index.d.ts:2429

___

### getEuler

▸ **getEuler**(`outerZ?`, `outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

根据四元数计算欧拉角，返回角度 x, y 在 [-180, 180] 区间内, z 默认在 [-90, 90] 区间内，旋转顺序为 YZX

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outerZ?` | `boolean` | usage:将z值范围更改为[-180，-90]U[90，180] default:false |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收结果的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

欧拉角

#### Defined in

Type/index.d.ts:2438

___

### getEulerAngles

▸ **getEulerAngles**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

返回当前四元数转化的欧拉角（x-y-z）。

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

欧拉角

#### Defined in

Type/index.d.ts:2365

___

### normalize

▸ **normalize**(): `void`

**`Description`**

将当前四元数归一化

**`Effect`**

调用端生效

#### Returns

`void`

#### Defined in

Type/index.d.ts:2405

___

### set

▸ **set**(`other`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

设置当前四元数使其与指定四元数相等。

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数数据 |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

`this`

#### Defined in

Type/index.d.ts:2343

▸ **set**(`x?`, `y?`, `z?`, `w?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

设置当前四元数指定元素值。

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x?` | `number` | usage:四元数的x分量 default:0 |
| `y?` | `number` | usage:四元数的y分量 default:0 |
| `z?` | `number` | usage:四元数的z分量 default:0 |
| `w?` | `number` | usage:四元数的w分量 default:0 |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

`this`

#### Defined in

Type/index.d.ts:2353

___

### setEulerAngles

▸ **setEulerAngles**(`euler`): `void`

**`Description`**

设置欧拉角

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `euler` | [`Vector`](Type.Type.Vector.md) | usage:传入的欧拉角 |

#### Returns

`void`

#### Defined in

Type/index.d.ts:2359

___

### strictEquals

▸ **strictEquals**(`other`): `boolean`

**`Description`**

判断当前四元数是否与指定四元数相等。

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Quaternion`](Type.Type.Quaternion.md) | usage:比对的目标四元数 |

#### Returns

`boolean`

比对后的结果

#### Defined in

Type/index.d.ts:2380

___

### toRotation

▸ **toRotation**(): [`Rotation`](Type.Type.Rotation.md)

**`Description`**

获取一个当前四元数的旋转数据

**`Effect`**

调用端生效

#### Returns

[`Rotation`](Type.Type.Rotation.md)

旋转数据

#### Defined in

Type/index.d.ts:2450

___

### toString

▸ **toString**(): `string`

**`Description`**

输出为字符串

**`Effect`**

调用端生效

#### Returns

`string`

四元数值字符串

#### Defined in

Type/index.d.ts:2456

___

### calculateW

▸ `Static` **calculateW**(`a`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

根据 xyz 分量计算 w 分量，默认已归一化

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:目标四元数 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2199

___

### conjugate

▸ `Static` **conjugate**(`a`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

求共轭四元数，对单位四元数与求逆等价，但更高效

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2277

___

### dot

▸ `Static` **dot**(`a`, `b`): `number`

**`Description`**

四元数点积（数量积）

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |

#### Returns

`number`

返回一个结果数

#### Defined in

Type/index.d.ts:2207

___

### equals

▸ `Static` **equals**(`a`, `b`, `epsilon?`): `boolean`

**`Description`**

排除浮点数误差的四元数近似等价判断

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |
| `epsilon?` | `number` | usage:最小误差数 default:MathDefine.EPSILON |

#### Returns

`boolean`

返回是否相等的结果

#### Defined in

Type/index.d.ts:2303

___

### fromAngleZ

▸ `Static` **fromAngleZ**(`z`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

根据 2D 角度（0, 0, z）计算四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `z` | `number` | usage:绕z旋转的角度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2078

___

### fromAxes

▸ `Static` **fromAxes**(`xAxis`, `yAxis`, `zAxis`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

根据坐标轴朝向计算四元数，默认三向量都已归一化且相互垂直

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `xAxis` | [`Vector`](Type.Type.Vector.md) | usage:x轴的向量值 |
| `yAxis` | [`Vector`](Type.Type.Vector.md) | usage:y轴的向量值 |
| `zAxis` | [`Vector`](Type.Type.Vector.md) | usage:z轴的向量值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2018

___

### fromAxisAngle

▸ `Static` **fromAxisAngle**(`axis`, `rad`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

根据旋转轴和旋转弧度计算四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `axis` | [`Vector`](Type.Type.Vector.md) | usage:旋转轴 |
| `rad` | `number` | usage:弧度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2047

___

### fromMatrix3x3

▸ `Static` **fromMatrix3x3**(`m`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

根据三维矩阵信息计算四元数，默认输入矩阵不含有缩放信息

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `m` | [`Matrix3x3`](Type.Type.Matrix3x3.md) | usage:三维矩阵 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2060

___

### fromRotation

▸ `Static` **fromRotation**(`v`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

读取旋转角数据创建或者写入一个四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `v` | [`Rotation`](Type.Type.Rotation.md) | usage:读取的字符串数据 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2007

___

### fromViewUp

▸ `Static` **fromViewUp**(`view`, `up?`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

根据视口的前方向和上方向计算四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `view` | [`Vector`](Type.Type.Vector.md) | usage:视口的前向量 |
| `up?` | [`Vector`](Type.Type.Vector.md) | usage:上方向量 default:null |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2033

___

### getAxis

▸ `Static` **getAxis**(`q`, `outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取四元数的旋转轴

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `q` | [`Quaternion`](Type.Type.Quaternion.md) | usage:目标四元数 |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:被写入的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

返回一个三维向量

#### Defined in

Type/index.d.ts:2097

___

### getAxisAngle

▸ `Static` **getAxisAngle**(`q`): `number`

**`Description`**

获取四元数的旋转弧度

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `q` | [`Quaternion`](Type.Type.Quaternion.md) | usage:目标四元数 |

#### Returns

`number`

返回一个弧度值

#### Defined in

Type/index.d.ts:2104

___

### invert

▸ `Static` **invert**(`a`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

四元数求逆

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2268

___

### lerp

▸ `Static` **lerp**(`a`, `b`, `t`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

逐元素线性插值： A + t * (B - A)

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |
| `t` | `number` | usage:插值（通常为0-1之间) |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2218

___

### multiply

▸ `Static` **multiply**(`a`, `b`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

四元数乘法

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2124

___

### multiplyVector

▸ `Static` **multiplyVector**(`a`, `q`, `outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

四元数乘以一个三维向量(通常用于向量通过四元数旋转)

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Vector`](Type.Type.Vector.md) | usage:目标向量 |
| `q` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数 |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:被写入的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

返回一个旋转后的三维向量

#### Defined in

Type/index.d.ts:2114

___

### normalize

▸ `Static` **normalize**(`a`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

归一化四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2286

___

### rotateAround

▸ `Static` **rotateAround**(`rot`, `axis`, `rad`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

绕世界空间下指定轴旋转四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rot` | [`Quaternion`](Type.Type.Quaternion.md) | usage:被旋转的四元数 |
| `axis` | [`Vector`](Type.Type.Vector.md) | usage:代表旋转轴的三维向量 |
| `rad` | `number` | usage:弧度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2169

___

### rotateAroundLocal

▸ `Static` **rotateAroundLocal**(`rot`, `axis`, `rad`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

绕本地空间下指定轴旋转四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `rot` | [`Quaternion`](Type.Type.Quaternion.md) | usage:需要变换的四元数 |
| `axis` | [`Vector`](Type.Type.Vector.md) | usage:代表旋转轴的三维向量 |
| `rad` | `number` | usage:弧度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2185

___

### rotateX

▸ `Static` **rotateX**(`a`, `rad`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

绕 X 轴旋转指定四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数 |
| `rad` | `number` | usage:弧度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2138

___

### rotateY

▸ `Static` **rotateY**(`a`, `rad`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

绕 Y 轴旋转指定四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数 |
| `rad` | `number` | usage:弧度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2148

___

### rotateZ

▸ `Static` **rotateZ**(`a`, `rad`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

绕 Z 轴旋转指定四元数

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数 |
| `rad` | `number` | usage:弧度值 |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2158

___

### rotationTo

▸ `Static` **rotationTo**(`a`, `b`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

设置四元数为两向量a和b间的最短路径旋转，默认两向量都已归一化

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Vector`](Type.Type.Vector.md) | usage:向量a |
| `b` | [`Vector`](Type.Type.Vector.md) | usage:向量b |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2088

___

### slerp

▸ `Static` **slerp**(`a`, `b`, `t`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

四元数球面插值

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |
| `t` | `number` | usage:插值（通常为0-1之间) |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2234

___

### sqlerp

▸ `Static` **sqlerp**(`a`, `b`, `c`, `d`, `t`, `outer?`): [`Quaternion`](Type.Type.Quaternion.md)

**`Description`**

带两个控制点的四元数球面插值

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Quaternion 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |
| `c` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数c |
| `d` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数d |
| `t` | `number` | usage:插值（通常为0-1之间) |
| `outer?` | [`Quaternion`](Type.Type.Quaternion.md) | usage:接收结果的 Quaternion 对象 default:null |

#### Returns

[`Quaternion`](Type.Type.Quaternion.md)

返回一个四元数

#### Defined in

Type/index.d.ts:2252

___

### strictEquals

▸ `Static` **strictEquals**(`a`, `b`): `boolean`

**`Description`**

四元数等价判断

**`Effect`**

调用端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `a` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数a |
| `b` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数b |

#### Returns

`boolean`

返回是否相等的结果

#### Defined in

Type/index.d.ts:2294

___

### toMatrix3x3

▸ `Static` **toMatrix3x3**(`q`, `outer?`): [`Matrix3x3`](Type.Type.Matrix3x3.md)

**`Description`**

根据四元数旋转信息计算矩阵

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Matrix3x3 对象, 建议传入 outer 来减少 new 对象且 outer 不能为 null/undefined

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `q` | [`Quaternion`](Type.Type.Quaternion.md) | usage:四元数信息 |
| `outer?` | [`Matrix3x3`](Type.Type.Matrix3x3.md) | usage:被写入的 Matrix3x3 对象 default:null |

#### Returns

[`Matrix3x3`](Type.Type.Matrix3x3.md)

返回一个三维矩阵

#### Defined in

Type/index.d.ts:2069
