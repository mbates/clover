[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / CloverClient

# Class: CloverClient

Defined in: [core/client.ts:44](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L44)

Main Clover client wrapper.

## Example

```typescript
const clover = createCloverClient({
  apiToken: process.env.CLOVER_API_TOKEN!,
  merchantId: process.env.CLOVER_MERCHANT_ID,
  environment: 'sandbox',
});

const charge = await clover.payments.create({
  amount: 1000, // $10.00
  source: 'clv_1TSTStok...',
});
```

## Constructors

### Constructor

> **new CloverClient**(`config`): `CloverClient`

Defined in: [core/client.ts:52](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L52)

#### Parameters

##### config

[`CloverClientConfig`](../interfaces/CloverClientConfig.md)

#### Returns

`CloverClient`

## Properties

### customers

> `readonly` **customers**: [`CustomersService`](CustomersService.md)

Defined in: [core/client.ts:50](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L50)

***

### payments

> `readonly` **payments**: [`PaymentsService`](PaymentsService.md)

Defined in: [core/client.ts:48](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L48)

***

### refunds

> `readonly` **refunds**: [`RefundsService`](RefundsService.md)

Defined in: [core/client.ts:49](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L49)

## Accessors

### environment

#### Get Signature

> **get** **environment**(): [`CloverEnvironment`](../type-aliases/CloverEnvironment.md)

Defined in: [core/client.ts:73](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L73)

The environment this client operates in.

##### Returns

[`CloverEnvironment`](../type-aliases/CloverEnvironment.md)

***

### merchantId

#### Get Signature

> **get** **merchantId**(): `string` \| `undefined`

Defined in: [core/client.ts:80](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/client.ts#L80)

The configured merchant id, if any.

##### Returns

`string` \| `undefined`
