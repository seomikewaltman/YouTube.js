[youtubei.js](../../../README.md) / [YTNodes](../README.md) / LiveChatPaidMessage

# Class: LiveChatPaidMessage

## Extends

- [`YTNode`](../../Helpers/classes/YTNode.md)

## Constructors

### new LiveChatPaidMessage()

> **new LiveChatPaidMessage**(`data`): [`LiveChatPaidMessage`](LiveChatPaidMessage.md)

#### Parameters

• **data**: [`RawNode`](../../APIResponseTypes/type-aliases/RawNode.md)

#### Returns

[`LiveChatPaidMessage`](LiveChatPaidMessage.md)

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`constructor`](../../Helpers/classes/YTNode.md#constructors)

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:22](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L22)

## Properties

### author

> **author**: [`Author`](../../Misc/classes/Author.md)

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:11](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L11)

***

### body\_background\_color

> **body\_background\_color**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:14](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L14)

***

### body\_text\_color

> **body\_text\_color**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:15](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L15)

***

### header\_background\_color

> **header\_background\_color**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:12](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L12)

***

### header\_text\_color

> **header\_text\_color**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:13](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L13)

***

### id

> **id**: `string`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:20](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L20)

***

### menu\_endpoint

> **menu\_endpoint**: [`NavigationEndpoint`](NavigationEndpoint.md)

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:17](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L17)

***

### message

> **message**: [`Text`](../../Misc/classes/Text.md)

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:10](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L10)

***

### purchase\_amount

> **purchase\_amount**: `string`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:16](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L16)

***

### timestamp

> **timestamp**: `number`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:18](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L18)

***

### timestamp\_text

> **timestamp\_text**: `string`

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:19](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L19)

***

### type

> `readonly` **type**: `string`

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type)

#### Defined in

[src/parser/helpers.ts:8](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/helpers.ts#L8)

***

### type

> `static` **type**: `string` = `'LiveChatPaidMessage'`

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type-1)

#### Defined in

[src/parser/classes/livechat/items/LiveChatPaidMessage.ts:8](https://github.com/LuanRT/YouTube.js/blob/305a398158a6cac82e6ef288fed4bf1661c89d52/src/parser/classes/livechat/items/LiveChatPaidMessage.ts#L8)

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

> **hasKey**\<`T`, `R`\>(`key`): `this is LiveChatPaidMessage & { [k in string]: R }`

Check for a key without asserting the type.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

`this is LiveChatPaidMessage & { [k in string]: R }`

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