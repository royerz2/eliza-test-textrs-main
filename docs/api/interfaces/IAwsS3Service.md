[@ai16z/eliza v0.1.5-alpha.5](../index.md) / IAwsS3Service

# Interface: IAwsS3Service

## Extends

- [`Service`](../classes/Service.md)

## Accessors

### serviceType

#### Get Signature

> **get** **serviceType**(): [`ServiceType`](../enumerations/ServiceType.md)

##### Returns

[`ServiceType`](../enumerations/ServiceType.md)

#### Inherited from

[`Service`](../classes/Service.md).[`serviceType`](../classes/Service.md#serviceType-1)

#### Defined in

[packages/core/src/types.ts:982](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L982)

## Methods

### initialize()

> `abstract` **initialize**(`runtime`): `Promise`\<`void`\>

Add abstract initialize method that must be implemented by derived classes

#### Parameters

• **runtime**: [`IAgentRuntime`](IAgentRuntime.md)

#### Returns

`Promise`\<`void`\>

#### Inherited from

[`Service`](../classes/Service.md).[`initialize`](../classes/Service.md#initialize)

#### Defined in

[packages/core/src/types.ts:987](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L987)

***

### uploadFile()

> **uploadFile**(`imagePath`, `useSignedUrl`, `expiresIn`): `Promise`\<`object`\>

#### Parameters

• **imagePath**: `string`

• **useSignedUrl**: `boolean`

• **expiresIn**: `number`

#### Returns

`Promise`\<`object`\>

##### success

> **success**: `boolean`

##### url?

> `optional` **url**: `string`

##### error?

> `optional` **error**: `string`

#### Defined in

[packages/core/src/types.ts:1141](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1141)

***

### generateSignedUrl()

> **generateSignedUrl**(`fileName`, `expiresIn`): `Promise`\<`string`\>

#### Parameters

• **fileName**: `string`

• **expiresIn**: `number`

#### Returns

`Promise`\<`string`\>

#### Defined in

[packages/core/src/types.ts:1146](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/types.ts#L1146)
