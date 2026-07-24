[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / parseWebhookEvent

# Function: parseWebhookEvent()

> **parseWebhookEvent**(`rawBody`): [`WebhookEvent`](../interfaces/WebhookEvent.md)

Defined in: [server/webhook.ts:136](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/webhook.ts#L136)

Parse a webhook request body into an event.

## Parameters

### rawBody

`string`

## Returns

[`WebhookEvent`](../interfaces/WebhookEvent.md)

## Throws

Error if the payload is not valid JSON
