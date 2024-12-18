[@ai16z/eliza v0.1.5-alpha.5](../index.md) / ICacheManager

# Interface: ICacheManager

## Methods

### get()

> **get**\<`T`\>(`key`): `Promise`\<`T`\>

#### Type Parameters

• **T** = `unknown`

#### Parameters

• **key**: `string`

#### Returns

`Promise`\<`T`\>

#### Defined in

[packages/core/src/types.ts:963](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L963)

***

### set()

> **set**\<`T`\>(`key`, `value`, `options`?): `Promise`\<`void`\>

#### Type Parameters

• **T**

#### Parameters

• **key**: `string`

• **value**: `T`

• **options?**: [`CacheOptions`](../type-aliases/CacheOptions.md)

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:964](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L964)

***

### delete()

> **delete**(`key`): `Promise`\<`void`\>

#### Parameters

• **key**: `string`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:965](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L965)
