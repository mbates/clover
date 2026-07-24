[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / processWebhookEvent

# Function: processWebhookEvent()

> **processWebhookEvent**(`event`, `config`): `Promise`\<`void`\>

Defined in: [server/webhook.ts:177](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/webhook.ts#L177)

Dispatch an event to the handler registered for its `type`.

## Parameters

### event

[`WebhookEvent`](../interfaces/WebhookEvent.md)

### config

[`WebhookConfig`](../interfaces/WebhookConfig.md)

## Returns

`Promise`\<`void`\>
