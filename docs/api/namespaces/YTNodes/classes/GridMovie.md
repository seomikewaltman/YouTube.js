[youtubei.js](../../../README.md) / [YTNodes](../README.md) / GridMovie

# Class: GridMovie

## Extends

- [`YTNode`](../../Helpers/classes/YTNode.md)

## Constructors

### new GridMovie()

> **new GridMovie**(`data`): [`GridMovie`](GridMovie.md)

#### Parameters

• **data**: [`RawNode`](../../APIResponseTypes/type-aliases/RawNode.md)

#### Returns

[`GridMovie`](GridMovie.md)

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`constructor`](../../Helpers/classes/YTNode.md#constructors)

#### Defined in

[src/parser/classes/GridMovie.ts:20](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L20)

## Properties

### badges

> **badges**: [`ObservedArray`](../../Helpers/type-aliases/ObservedArray.md)\<[`MetadataBadge`](MetadataBadge.md)\>

#### Defined in

[src/parser/classes/GridMovie.ts:16](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L16)

***

### duration

> **duration**: `null` \| [`Text`](../../Misc/classes/Text.md)

#### Defined in

[src/parser/classes/GridMovie.ts:14](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L14)

***

### endpoint

> **endpoint**: [`NavigationEndpoint`](NavigationEndpoint.md)

#### Defined in

[src/parser/classes/GridMovie.ts:15](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L15)

***

### id

> **id**: `string`

#### Defined in

[src/parser/classes/GridMovie.ts:11](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L11)

***

### metadata

> **metadata**: [`Text`](../../Misc/classes/Text.md)

#### Defined in

[src/parser/classes/GridMovie.ts:17](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L17)

***

### thumbnail\_overlays

> **thumbnail\_overlays**: [`ObservedArray`](../../Helpers/type-aliases/ObservedArray.md)\<[`YTNode`](../../Helpers/classes/YTNode.md)\>

#### Defined in

[src/parser/classes/GridMovie.ts:18](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L18)

***

### thumbnails

> **thumbnails**: [`Thumbnail`](../../Misc/classes/Thumbnail.md)[]

#### Defined in

[src/parser/classes/GridMovie.ts:13](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L13)

***

### title

> **title**: [`Text`](../../Misc/classes/Text.md)

#### Defined in

[src/parser/classes/GridMovie.ts:12](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L12)

***

### type

> `readonly` **type**: `string`

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type)

#### Defined in

[src/parser/helpers.ts:8](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L8)

***

### type

> `static` **type**: `string` = `'GridMovie'`

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type-1)

#### Defined in

[src/parser/classes/GridMovie.ts:9](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/GridMovie.ts#L9)

## Methods

### as()

> **as**\<`T`, `K`\>(...`types`): `InstanceType`\<`K`\[`number`\]\>

Cast to one of the given types.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

#### Returns

`InstanceType`\<`K`\[`number`\]\>

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`as`](../../Helpers/classes/YTNode.md#as)

#### Defined in

[src/parser/helpers.ts:35](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L35)

***

### hasKey()

> **hasKey**\<`T`, `R`\>(`key`): `this is GridMovie & { [k in string]: R }`

Check for a key without asserting the type.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

`this is GridMovie & { [k in string]: R }`

Whether the node has the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`hasKey`](../../Helpers/classes/YTNode.md#haskey)

#### Defined in

[src/parser/helpers.ts:47](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L47)

***

### is()

> **is**\<`T`, `K`\>(...`types`): `this is InstanceType<K[number]>`

Check if the node is of the given type.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The type to check

#### Returns

`this is InstanceType<K[number]>`

whether the node is of the given type

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`is`](../../Helpers/classes/YTNode.md#is)

#### Defined in

[src/parser/helpers.ts:28](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L28)

***

### key()

> **key**\<`T`, `R`\>(`key`): [`Maybe`](../../Helpers/classes/Maybe.md)

Assert that the node has the given key and return it.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

[`Maybe`](../../Helpers/classes/Maybe.md)

The value of the key wrapped in a Maybe

#### Throws

If the node does not have the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`key`](../../Helpers/classes/YTNode.md#key)

#### Defined in

[src/parser/helpers.ts:57](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L57)