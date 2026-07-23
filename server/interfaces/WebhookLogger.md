[**@bates-solutions/clover API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / WebhookLogger

# Interface: WebhookLogger

Defined in: [server/middleware/lambda.ts:32](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/server/middleware/lambda.ts#L32)

Logger interface for the Lambda webhook handler.

## Properties

### error

> **error**: (`message`, `data?`) => `void`

Defined in: [server/middleware/lambda.ts:34](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/server/middleware/lambda.ts#L34)

#### Parameters

##### message

`string`

##### data?

`Record`\<`string`, `unknown`\>

#### Returns

`void`

***

### info

> **info**: (`message`, `data?`) => `void`

Defined in: [server/middleware/lambda.ts:33](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/server/middleware/lambda.ts#L33)

#### Parameters

##### message

`string`

##### data?

`Record`\<`string`, `unknown`\>

#### Returns

`void`
