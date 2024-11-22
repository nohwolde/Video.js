[youtubei.js](../../../README.md) / [YTNodes](../README.md) / LiveChatItemContextMenuEndpoint

# Class: LiveChatItemContextMenuEndpoint

## Extends

- [`YTNode`](../../Helpers/classes/YTNode.md)

## Implements

- [`IEndpoint`](../../APIResponseTypes/interfaces/IEndpoint.md)\<[`LiveChatItemContextMenuRequest`](../../APIResponseTypes/type-aliases/LiveChatItemContextMenuRequest.md)\>

## Constructors

### new LiveChatItemContextMenuEndpoint()

> **new LiveChatItemContextMenuEndpoint**(`data`): [`LiveChatItemContextMenuEndpoint`](LiveChatItemContextMenuEndpoint.md)

#### Parameters

• **data**: [`RawNode`](../../APIResponseTypes/type-aliases/RawNode.md)

#### Returns

[`LiveChatItemContextMenuEndpoint`](LiveChatItemContextMenuEndpoint.md)

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`constructor`](../../Helpers/classes/YTNode.md#constructors)

#### Defined in

[src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts:10](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts#L10)

## Properties

### type

> `readonly` **type**: `string`

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type)

#### Defined in

[src/parser/helpers.ts:8](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/helpers.ts#L8)

***

### type

> `static` **type**: `string` = `'LiveChatItemContextMenuEndpoint'`

#### Overrides

[`YTNode`](../../Helpers/classes/YTNode.md).[`type`](../../Helpers/classes/YTNode.md#type-1)

#### Defined in

[src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts:5](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts#L5)

## Methods

### as()

> **as**\<`T`, `K`\>(...`types`): `InstanceType`\<`K`\[`number`\]\>

Cast to one of the given types.

#### Type Parameters

• **T** *extends* [`YTNode`](../../Helpers/classes/YTNode.md)

• **K** *extends* [`YTNodeConstructor`](../../Helpers/interfaces/YTNodeConstructor.md)\<`T`\>[]

#### Parameters

• ...**types**: `K`

The types to cast to

#### Returns

`InstanceType`\<`K`\[`number`\]\>

The node cast to one of the given types

#### Throws

If the node is not of the given type

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`as`](../../Helpers/classes/YTNode.md#as)

#### Defined in

[src/parser/helpers.ts:38](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/helpers.ts#L38)

***

### buildRequest()

> **buildRequest**(): [`LiveChatItemContextMenuRequest`](../../APIResponseTypes/type-aliases/LiveChatItemContextMenuRequest.md)

#### Returns

[`LiveChatItemContextMenuRequest`](../../APIResponseTypes/type-aliases/LiveChatItemContextMenuRequest.md)

#### Implementation of

[`IEndpoint`](../../APIResponseTypes/interfaces/IEndpoint.md).[`buildRequest`](../../APIResponseTypes/interfaces/IEndpoint.md#buildrequest)

#### Defined in

[src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts:19](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts#L19)

***

### getApiPath()

> **getApiPath**(): `string`

#### Returns

`string`

#### Implementation of

[`IEndpoint`](../../APIResponseTypes/interfaces/IEndpoint.md).[`getApiPath`](../../APIResponseTypes/interfaces/IEndpoint.md#getapipath)

#### Defined in

[src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts:15](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/classes/endpoints/LiveChatItemContextMenuEndpoint.ts#L15)

***

### hasKey()

> **hasKey**\<`T`, `R`\>(`key`): `this is LiveChatItemContextMenuEndpoint & { [k in string]: R }`

Check for a key without asserting the type.

#### Type Parameters

• **T** *extends* `string`

• **R** = `any`

#### Parameters

• **key**: `T`

The key to check

#### Returns

`this is LiveChatItemContextMenuEndpoint & { [k in string]: R }`

Whether the node has the key

#### Inherited from

[`YTNode`](../../Helpers/classes/YTNode.md).[`hasKey`](../../Helpers/classes/YTNode.md#haskey)

#### Defined in

[src/parser/helpers.ts:50](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/helpers.ts#L50)

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

[src/parser/helpers.ts:28](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/helpers.ts#L28)

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

[src/parser/helpers.ts:60](https://github.com/LuanRT/YouTube.js/blob/cf09f7bab14fcca99e1f3ae428c7337fea58cfa5/src/parser/helpers.ts#L60)