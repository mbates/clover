[**@bates-solutions/clover API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / CaptureChargeOptions

# Interface: CaptureChargeOptions

Defined in: [core/services/payments.service.ts:29](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/services/payments.service.ts#L29)

Options for capturing a previously authorized charge.

## Properties

### amount?

> `optional` **amount?**: `number`

Defined in: [core/services/payments.service.ts:31](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/services/payments.service.ts#L31)

Amount in cents to capture (defaults to the full authorized amount)

***

### idempotencyKey?

> `optional` **idempotencyKey?**: `string`

Defined in: [core/services/payments.service.ts:32](https://github.com/mbates/clover/blob/592e3fabe4288305c56c6720838cf241d5dd7546/src/core/services/payments.service.ts#L32)
