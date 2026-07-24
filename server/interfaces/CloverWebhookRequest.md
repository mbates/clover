[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / CloverWebhookRequest

# Interface: CloverWebhookRequest

Defined in: [server/middleware/express.ts:14](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/middleware/express.ts#L14)

Extended Express Request carrying Clover webhook data.

## Extends

- `Request`

## Properties

### cloverEvent?

> `optional` **cloverEvent?**: [`WebhookEvent`](WebhookEvent.md)

Defined in: [server/middleware/express.ts:16](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/middleware/express.ts#L16)

***

### rawBody?

> `optional` **rawBody?**: `string`

Defined in: [server/middleware/express.ts:15](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/middleware/express.ts#L15)
