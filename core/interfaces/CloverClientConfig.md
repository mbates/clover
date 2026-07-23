[**@bates-solutions/clover API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / CloverClientConfig

# Interface: CloverClientConfig

Defined in: [core/client.ts:10](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/client.ts#L10)

Configuration options for the Clover client.

## Properties

### apiToken

> **apiToken**: `string`

Defined in: [core/client.ts:12](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/client.ts#L12)

Clover API token (OAuth access token or API key)

***

### environment?

> `optional` **environment?**: [`CloverEnvironment`](../type-aliases/CloverEnvironment.md)

Defined in: [core/client.ts:22](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/client.ts#L22)

Environment.

#### Default

```ts
'sandbox'
```

***

### fetchImpl?

> `optional` **fetchImpl?**: \{(`input`, `init?`): `Promise`\<`Response`\>; (`input`, `init?`): `Promise`\<`Response`\>; \}

Defined in: [core/client.ts:24](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/client.ts#L24)

Override the `fetch` implementation (mainly for tests).

#### Call Signature

> (`input`, `init?`): `Promise`\<`Response`\>

[MDN Reference](https://developer.mozilla.org/docs/Web/API/Window/fetch)

##### Parameters

###### input

`URL` \| `RequestInfo`

###### init?

`RequestInit`

##### Returns

`Promise`\<`Response`\>

#### Call Signature

> (`input`, `init?`): `Promise`\<`Response`\>

[MDN Reference](https://developer.mozilla.org/docs/Web/API/Window/fetch)

##### Parameters

###### input

`string` \| `URL` \| `Request`

###### init?

`RequestInit`

##### Returns

`Promise`\<`Response`\>

***

### merchantId?

> `optional` **merchantId?**: `string`

Defined in: [core/client.ts:17](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/client.ts#L17)

Merchant id. Required for platform (`/v3/merchants/{mId}`) operations such
as `customers`; not needed for Ecommerce charges/refunds.
