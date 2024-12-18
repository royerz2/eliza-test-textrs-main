[@ai16z/eliza v0.1.5-alpha.5](../index.md) / GenerationOptions

# Interface: GenerationOptions

Configuration options for generating objects with a model.

## Properties

### runtime

> **runtime**: [`IAgentRuntime`](IAgentRuntime.md)

#### Defined in

[packages/core/src/generation.ts:1198](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1198)

***

### context

> **context**: `string`

#### Defined in

[packages/core/src/generation.ts:1199](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1199)

***

### modelClass

> **modelClass**: [`ModelClass`](../enumerations/ModelClass.md)

#### Defined in

[packages/core/src/generation.ts:1200](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1200)

***

### schema?

> `optional` **schema**: `ZodType`\<`any`, `ZodTypeDef`, `any`\>

#### Defined in

[packages/core/src/generation.ts:1201](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1201)

***

### schemaName?

> `optional` **schemaName**: `string`

#### Defined in

[packages/core/src/generation.ts:1202](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1202)

***

### schemaDescription?

> `optional` **schemaDescription**: `string`

#### Defined in

[packages/core/src/generation.ts:1203](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1203)

***

### stop?

> `optional` **stop**: `string`[]

#### Defined in

[packages/core/src/generation.ts:1204](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1204)

***

### mode?

> `optional` **mode**: `"auto"` \| `"json"` \| `"tool"`

#### Defined in

[packages/core/src/generation.ts:1205](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1205)

***

### experimental\_providerMetadata?

> `optional` **experimental\_providerMetadata**: `Record`\<`string`, `unknown`\>

#### Defined in

[packages/core/src/generation.ts:1206](https://github.com/royerz2/eliza-test-textrs-main/blob/main/packages/core/src/generation.ts#L1206)
