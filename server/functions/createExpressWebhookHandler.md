[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / createExpressWebhookHandler

# Function: createExpressWebhookHandler()

> **createExpressWebhookHandler**(`config`): `RequestHandler`

Defined in: [server/middleware/express.ts:41](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/middleware/express.ts#L41)

Create Express middleware for handling Clover webhooks.

Mount the raw body parser on the webhook route so the signature can be
verified against the exact bytes:

```typescript
app.use('/webhook', express.raw({ type: 'application/json' }));
app.post('/webhook', createExpressWebhookHandler({ signingSecret, handlers }));
```

## Parameters

### config

[`ExpressWebhookOptions`](../interfaces/ExpressWebhookOptions.md)

## Returns

`RequestHandler`
