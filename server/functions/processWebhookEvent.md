[**@bates-solutions/clover API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / processWebhookEvent

# Function: processWebhookEvent()

> **processWebhookEvent**(`event`, `config`): `Promise`\<`void`\>

Defined in: [server/webhook.ts:177](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/server/webhook.ts#L177)

Dispatch an event to the handler registered for its `type`.

## Parameters

### event

[`WebhookEvent`](../interfaces/WebhookEvent.md)

### config

[`WebhookConfig`](../interfaces/WebhookConfig.md)

## Returns

`Promise`\<`void`\>
