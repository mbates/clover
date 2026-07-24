[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [server](../README.md) / getVerificationCode

# Function: getVerificationCode()

> **getVerificationCode**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:150](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/server/webhook.ts#L150)

The verification code Clover sends when first validating a webhook URL.

Clover POSTs `{ "verificationCode": "..." }` (with no signature) to confirm
the endpoint; respond `200` to complete setup.

## Parameters

### event

[`WebhookEvent`](../interfaces/WebhookEvent.md)

## Returns

`string` \| `undefined`
