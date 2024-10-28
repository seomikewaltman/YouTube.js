[youtubei.js](../README.md) / MusicShelfContinuation

# Class: MusicShelfContinuation

## Extends

- [`YTNode`](../namespaces/Helpers/classes/YTNode.md)

## Constructors

### new MusicShelfContinuation()

> **new MusicShelfContinuation**(`data`): [`MusicShelfContinuation`](MusicShelfContinuation.md)

#### Parameters

• **data**: [`RawNode`](../namespaces/APIResponseTypes/type-aliases/RawNode.md)

#### Returns

[`MusicShelfContinuation`](MusicShelfContinuation.md)

#### Overrides

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`constructor`](../namespaces/Helpers/classes/YTNode.md#constructors)

#### Defined in

[src/parser/continuations.ts:99](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/continuations.ts#L99)

## Properties

### contents

> **contents**: `null` \| [`ObservedArray`](../namespaces/Helpers/type-aliases/ObservedArray.md)\<[`YTNode`](../namespaces/Helpers/classes/YTNode.md)\>

#### Defined in

[src/parser/continuations.ts:97](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/continuations.ts#L97)

***

### continuation

> **continuation**: `string`

#### Defined in

[src/parser/continuations.ts:96](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/continuations.ts#L96)

***

### type

> `readonly` **type**: `string`

#### Inherited from

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`type`](../namespaces/Helpers/classes/YTNode.md#type)

#### Defined in

[src/parser/helpers.ts:8](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L8)

***

### type

> `readonly` `static` **type**: `"musicShelfContinuation"` = `'musicShelfContinuation'`

#### Overrides

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`type`](../namespaces/Helpers/classes/YTNode.md#type-1)

#### Defined in

[src/parser/continuations.ts:94](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/continuations.ts#L94)

## Methods

### as()

> **as**\<`T`, `K`\>(...`types`): `InstanceType`\<`K`\[`number`\]\>

Cast to one of the given types.

#### Type Parameters

• **T** *extends* [`YTNode`](../namespaces/Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../namespaces/Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

#### Returns

`InstanceType`\<`K`\[`number`\]\>

#### Inherited from

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`as`](../namespaces/Helpers/classes/YTNode.md#as)

#### Defined in

[src/parser/helpers.ts:35](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L35)

***

### hasKey()

> **hasKey**\<`T`, `R`\>(`key`): `this is MusicShelfContinuation & { [k in string]: R }`

Check for a key without asserting the type.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

`this is MusicShelfContinuation & { [k in string]: R }`

Whether the node has the key

#### Inherited from

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`hasKey`](../namespaces/Helpers/classes/YTNode.md#haskey)

#### Defined in

[src/parser/helpers.ts:47](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L47)

***

### is()

> **is**\<`T`, `K`\>(...`types`): `this is InstanceType<K[number]>`

Check if the node is of the given type.

#### Type Parameters

• **T** *extends* [`YTNode`](../namespaces/Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../namespaces/Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The type to check

#### Returns

`this is InstanceType<K[number]>`

whether the node is of the given type

#### Inherited from

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`is`](../namespaces/Helpers/classes/YTNode.md#is)

#### Defined in

[src/parser/helpers.ts:28](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L28)

***

### key()

> **key**\<`T`, `R`\>(`key`): [`Maybe`](../namespaces/Helpers/classes/Maybe.md)

Assert that the node has the given key and return it.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

[`Maybe`](../namespaces/Helpers/classes/Maybe.md)

The value of the key wrapped in a Maybe

#### Throws

If the node does not have the key

#### Inherited from

[`YTNode`](../namespaces/Helpers/classes/YTNode.md).[`key`](../namespaces/Helpers/classes/YTNode.md#key)

#### Defined in

[src/parser/helpers.ts:57](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L57)