[**@bates-solutions/clover API Reference v1.0.3**](../README.md)

***

[@bates-solutions/clover API Reference](../README.md) / core

# core

`@bates-solutions/clover` — a TypeScript wrapper for the Clover Ecommerce and
Platform APIs.

The package's main entrypoint. Exports `createCloverClient` / `CloverClient`
(one service per Clover domain — `payments`, `refunds`, `customers`), the
normalized error hierarchy (`CloverError` + `parseCloverError`), and money /
idempotency utilities. It ships no vendor SDK — it talks to Clover over a
small fetch-based REST client that targets both Clover hosts. Webhook helpers
live in the `@bates-solutions/clover/server` entrypoint.

## Example

```ts
import { createCloverClient } from '@bates-solutions/clover';

const clover = createCloverClient({ apiToken: process.env.CLOVER_API_TOKEN! });
const charge = await clover.payments.create({ amount: 1000, source: 'clv_tok' });
```

## Classes

- [CloverApiError](classes/CloverApiError.md)
- [CloverAuthError](classes/CloverAuthError.md)
- [CloverClient](classes/CloverClient.md)
- [CloverError](classes/CloverError.md)
- [CloverHttp](classes/CloverHttp.md)
- [CloverPaymentError](classes/CloverPaymentError.md)
- [CloverValidationError](classes/CloverValidationError.md)
- [CustomersService](classes/CustomersService.md)
- [PaymentsService](classes/PaymentsService.md)
- [RefundsService](classes/RefundsService.md)

## Interfaces

- [CaptureChargeOptions](interfaces/CaptureChargeOptions.md)
- [Charge](interfaces/Charge.md)
- [CloverClientConfig](interfaces/CloverClientConfig.md)
- [CloverHttpConfig](interfaces/CloverHttpConfig.md)
- [CreateChargeOptions](interfaces/CreateChargeOptions.md)
- [CreateCustomerOptions](interfaces/CreateCustomerOptions.md)
- [CreateRefundOptions](interfaces/CreateRefundOptions.md)
- [Customer](interfaces/Customer.md)
- [Money](interfaces/Money.md)
- [PaginatedResponse](interfaces/PaginatedResponse.md)
- [PaginationOptions](interfaces/PaginationOptions.md)
- [Refund](interfaces/Refund.md)
- [RequestOptions](interfaces/RequestOptions.md)

## Type Aliases

- [CloverEnvironment](type-aliases/CloverEnvironment.md)
- [CloverErrorCode](type-aliases/CloverErrorCode.md)
- [CloverHost](type-aliases/CloverHost.md)
- [CurrencyCode](type-aliases/CurrencyCode.md)
- [UpdateCustomerOptions](type-aliases/UpdateCustomerOptions.md)

## Functions

- [createCloverClient](functions/createCloverClient.md)
- [createIdempotencyKey](functions/createIdempotencyKey.md)
- [formatMoney](functions/formatMoney.md)
- [fromCents](functions/fromCents.md)
- [parseCloverError](functions/parseCloverError.md)
- [toCents](functions/toCents.md)
