[**@bates-solutions/clover API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / RequestOptions

# Interface: RequestOptions

Defined in: [core/http.ts:37](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/http.ts#L37)

Options for a single request.

## Properties

### body?

> `optional` **body?**: `unknown`

Defined in: [core/http.ts:41](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/http.ts#L41)

JSON request body

***

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/http.ts:43](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/http.ts#L43)

Idempotency key, sent as the `idempotency-key` header

***

### query?

> `optional` **query?**: `Record`\<`string`, `string` \| `number` \| `undefined`\>

Defined in: [core/http.ts:39](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/http.ts#L39)

Query-string parameters
