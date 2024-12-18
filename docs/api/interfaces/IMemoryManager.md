[@ai16z/eliza v0.1.5-alpha.5](../index.md) / IMemoryManager

# Interface: IMemoryManager

## Properties

### runtime

> **runtime**: [`IAgentRuntime`](IAgentRuntime.md)

#### Defined in

[packages/core/src/types.ts:919](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L919)

***

### tableName

> **tableName**: `string`

#### Defined in

[packages/core/src/types.ts:920](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L920)

***

### constructor

> **constructor**: `Function`

#### Defined in

[packages/core/src/types.ts:921](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L921)

## Methods

### addEmbeddingToMemory()

> **addEmbeddingToMemory**(`memory`): `Promise`\<[`Memory`](Memory.md)\>

#### Parameters

• **memory**: [`Memory`](Memory.md)

#### Returns

`Promise`\<[`Memory`](Memory.md)\>

#### Defined in

[packages/core/src/types.ts:923](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L923)

***

### getMemories()

> **getMemories**(`opts`): `Promise`\<[`Memory`](Memory.md)[]\>

#### Parameters

• **opts**

• **opts.roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **opts.count?**: `number`

• **opts.unique?**: `boolean`

• **opts.start?**: `number`

• **opts.end?**: `number`

#### Returns

`Promise`\<[`Memory`](Memory.md)[]\>

#### Defined in

[packages/core/src/types.ts:925](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L925)

***

### getCachedEmbeddings()

> **getCachedEmbeddings**(`content`): `Promise`\<`object`[]\>

#### Parameters

• **content**: `string`

#### Returns

`Promise`\<`object`[]\>

#### Defined in

[packages/core/src/types.ts:933](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L933)

***

### getMemoryById()

> **getMemoryById**(`id`): `Promise`\<[`Memory`](Memory.md)\>

#### Parameters

• **id**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Returns

`Promise`\<[`Memory`](Memory.md)\>

#### Defined in

[packages/core/src/types.ts:937](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L937)

***

### getMemoriesByRoomIds()

> **getMemoriesByRoomIds**(`params`): `Promise`\<[`Memory`](Memory.md)[]\>

#### Parameters

• **params**

• **params.roomIds**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`[]

#### Returns

`Promise`\<[`Memory`](Memory.md)[]\>

#### Defined in

[packages/core/src/types.ts:938](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L938)

***

### searchMemoriesByEmbedding()

> **searchMemoriesByEmbedding**(`embedding`, `opts`): `Promise`\<[`Memory`](Memory.md)[]\>

#### Parameters

• **embedding**: `number`[]

• **opts**

• **opts.match\_threshold?**: `number`

• **opts.count?**: `number`

• **opts.roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **opts.unique?**: `boolean`

#### Returns

`Promise`\<[`Memory`](Memory.md)[]\>

#### Defined in

[packages/core/src/types.ts:939](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L939)

***

### createMemory()

> **createMemory**(`memory`, `unique`?): `Promise`\<`void`\>

#### Parameters

• **memory**: [`Memory`](Memory.md)

• **unique?**: `boolean`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:949](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L949)

***

### removeMemory()

> **removeMemory**(`memoryId`): `Promise`\<`void`\>

#### Parameters

• **memoryId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:951](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L951)

***

### removeAllMemories()

> **removeAllMemories**(`roomId`): `Promise`\<`void`\>

#### Parameters

• **roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:953](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L953)

***

### countMemories()

> **countMemories**(`roomId`, `unique`?): `Promise`\<`number`\>

#### Parameters

• **roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **unique?**: `boolean`

#### Returns

`Promise`\<`number`\>

#### Defined in

[packages/core/src/types.ts:955](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L955)
