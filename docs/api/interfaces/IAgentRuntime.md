[@ai16z/eliza v0.1.5-alpha.5](../index.md) / IAgentRuntime

# Interface: IAgentRuntime

## Properties

### agentId

> **agentId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

Properties

#### Defined in

[packages/core/src/types.ts:992](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L992)

***

### serverUrl

> **serverUrl**: `string`

#### Defined in

[packages/core/src/types.ts:993](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L993)

***

### databaseAdapter

> **databaseAdapter**: [`IDatabaseAdapter`](IDatabaseAdapter.md)

#### Defined in

[packages/core/src/types.ts:994](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L994)

***

### token

> **token**: `string`

#### Defined in

[packages/core/src/types.ts:995](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L995)

***

### modelProvider

> **modelProvider**: [`ModelProviderName`](../enumerations/ModelProviderName.md)

#### Defined in

[packages/core/src/types.ts:996](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L996)

***

### imageModelProvider

> **imageModelProvider**: [`ModelProviderName`](../enumerations/ModelProviderName.md)

#### Defined in

[packages/core/src/types.ts:997](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L997)

***

### character

> **character**: [`Character`](../type-aliases/Character.md)

#### Defined in

[packages/core/src/types.ts:998](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L998)

***

### providers

> **providers**: [`Provider`](Provider.md)[]

#### Defined in

[packages/core/src/types.ts:999](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L999)

***

### actions

> **actions**: [`Action`](Action.md)[]

#### Defined in

[packages/core/src/types.ts:1000](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1000)

***

### evaluators

> **evaluators**: [`Evaluator`](Evaluator.md)[]

#### Defined in

[packages/core/src/types.ts:1001](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1001)

***

### plugins

> **plugins**: [`Plugin`](../type-aliases/Plugin.md)[]

#### Defined in

[packages/core/src/types.ts:1002](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1002)

***

### fetch()?

> `optional` **fetch**: (`input`, `init`?) => `Promise`\<`Response`\>(`input`, `init`?) => `Promise`\<`Response`\>

[MDN Reference](https://developer.mozilla.org/docs/Web/API/fetch)

#### Parameters

• **input**: `RequestInfo` \| `URL`

• **init?**: `RequestInit`

#### Returns

`Promise`\<`Response`\>

#### Parameters

• **input**: `string` \| `Request` \| `URL`

• **init?**: `RequestInit`

#### Returns

`Promise`\<`Response`\>

#### Defined in

[packages/core/src/types.ts:1004](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1004)

***

### messageManager

> **messageManager**: [`IMemoryManager`](IMemoryManager.md)

#### Defined in

[packages/core/src/types.ts:1006](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1006)

***

### descriptionManager

> **descriptionManager**: [`IMemoryManager`](IMemoryManager.md)

#### Defined in

[packages/core/src/types.ts:1007](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1007)

***

### documentsManager

> **documentsManager**: [`IMemoryManager`](IMemoryManager.md)

#### Defined in

[packages/core/src/types.ts:1008](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1008)

***

### knowledgeManager

> **knowledgeManager**: [`IMemoryManager`](IMemoryManager.md)

#### Defined in

[packages/core/src/types.ts:1009](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1009)

***

### loreManager

> **loreManager**: [`IMemoryManager`](IMemoryManager.md)

#### Defined in

[packages/core/src/types.ts:1010](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1010)

***

### cacheManager

> **cacheManager**: [`ICacheManager`](ICacheManager.md)

#### Defined in

[packages/core/src/types.ts:1012](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1012)

***

### services

> **services**: `Map`\<[`ServiceType`](../enumerations/ServiceType.md), [`Service`](../classes/Service.md)\>

#### Defined in

[packages/core/src/types.ts:1014](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1014)

***

### clients

> **clients**: `Record`\<`string`, `any`\>

any could be EventEmitter
but I think the real solution is forthcoming as a base client interface

#### Defined in

[packages/core/src/types.ts:1017](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1017)

## Methods

### initialize()

> **initialize**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1019](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1019)

***

### registerMemoryManager()

> **registerMemoryManager**(`manager`): `void`

#### Parameters

• **manager**: [`IMemoryManager`](IMemoryManager.md)

#### Returns

`void`

#### Defined in

[packages/core/src/types.ts:1021](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1021)

***

### getMemoryManager()

> **getMemoryManager**(`name`): [`IMemoryManager`](IMemoryManager.md)

#### Parameters

• **name**: `string`

#### Returns

[`IMemoryManager`](IMemoryManager.md)

#### Defined in

[packages/core/src/types.ts:1023](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1023)

***

### getService()

> **getService**\<`T`\>(`service`): `T`

#### Type Parameters

• **T** *extends* [`Service`](../classes/Service.md)

#### Parameters

• **service**: [`ServiceType`](../enumerations/ServiceType.md)

#### Returns

`T`

#### Defined in

[packages/core/src/types.ts:1025](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1025)

***

### registerService()

> **registerService**(`service`): `void`

#### Parameters

• **service**: [`Service`](../classes/Service.md)

#### Returns

`void`

#### Defined in

[packages/core/src/types.ts:1027](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1027)

***

### getSetting()

> **getSetting**(`key`): `string`

#### Parameters

• **key**: `string`

#### Returns

`string`

#### Defined in

[packages/core/src/types.ts:1029](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1029)

***

### getConversationLength()

> **getConversationLength**(): `number`

Methods

#### Returns

`number`

#### Defined in

[packages/core/src/types.ts:1032](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1032)

***

### processActions()

> **processActions**(`message`, `responses`, `state`?, `callback`?): `Promise`\<`void`\>

#### Parameters

• **message**: [`Memory`](Memory.md)

• **responses**: [`Memory`](Memory.md)[]

• **state?**: [`State`](State.md)

• **callback?**: [`HandlerCallback`](../type-aliases/HandlerCallback.md)

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1034](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1034)

***

### evaluate()

> **evaluate**(`message`, `state`?, `didRespond`?, `callback`?): `Promise`\<`string`[]\>

#### Parameters

• **message**: [`Memory`](Memory.md)

• **state?**: [`State`](State.md)

• **didRespond?**: `boolean`

• **callback?**: [`HandlerCallback`](../type-aliases/HandlerCallback.md)

#### Returns

`Promise`\<`string`[]\>

#### Defined in

[packages/core/src/types.ts:1041](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1041)

***

### ensureParticipantExists()

> **ensureParticipantExists**(`userId`, `roomId`): `Promise`\<`void`\>

#### Parameters

• **userId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1048](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1048)

***

### ensureUserExists()

> **ensureUserExists**(`userId`, `userName`, `name`, `source`): `Promise`\<`void`\>

#### Parameters

• **userId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **userName**: `string`

• **name**: `string`

• **source**: `string`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1050](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1050)

***

### registerAction()

> **registerAction**(`action`): `void`

#### Parameters

• **action**: [`Action`](Action.md)

#### Returns

`void`

#### Defined in

[packages/core/src/types.ts:1057](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1057)

***

### ensureConnection()

> **ensureConnection**(`userId`, `roomId`, `userName`?, `userScreenName`?, `source`?): `Promise`\<`void`\>

#### Parameters

• **userId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **userName?**: `string`

• **userScreenName?**: `string`

• **source?**: `string`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1059](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1059)

***

### ensureParticipantInRoom()

> **ensureParticipantInRoom**(`userId`, `roomId`): `Promise`\<`void`\>

#### Parameters

• **userId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

• **roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1067](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1067)

***

### ensureRoomExists()

> **ensureRoomExists**(`roomId`): `Promise`\<`void`\>

#### Parameters

• **roomId**: \`$\{string\}-$\{string\}-$\{string\}-$\{string\}-$\{string\}\`

#### Returns

`Promise`\<`void`\>

#### Defined in

[packages/core/src/types.ts:1069](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1069)

***

### composeState()

> **composeState**(`message`, `additionalKeys`?): `Promise`\<[`State`](State.md)\>

#### Parameters

• **message**: [`Memory`](Memory.md)

• **additionalKeys?**

#### Returns

`Promise`\<[`State`](State.md)\>

#### Defined in

[packages/core/src/types.ts:1071](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1071)

***

### updateRecentMessageState()

> **updateRecentMessageState**(`state`): `Promise`\<[`State`](State.md)\>

#### Parameters

• **state**: [`State`](State.md)

#### Returns

`Promise`\<[`State`](State.md)\>

#### Defined in

[packages/core/src/types.ts:1076](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1076)
