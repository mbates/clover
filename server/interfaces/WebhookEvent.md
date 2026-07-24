[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / WebhookEvent

# Interface: WebhookEvent

Defined in: [server/types.ts:8](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/types.ts#L8)

A parsed Clover webhook event.

Clover webhook payloads vary by product (Hosted Checkout vs platform app
webhooks), so the event is kept generic — dispatch is keyed off an optional
`type` field when present.

## Indexable

> \[`key`: `string`\]: `unknown`

## Properties

### type?

> `optional` **type?**: `string`

Defined in: [server/types.ts:10](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/types.ts#L10)

Event type, when the payload carries one
