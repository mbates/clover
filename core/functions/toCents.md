[**@bates-solutions/clover API Reference v1.0.3**](../../README.md)

***

[@bates-solutions/clover API Reference](../../README.md) / [core](../README.md) / toCents

# Function: toCents()

> **toCents**(`amount`): `number`

Defined in: [core/utils.ts:23](https://github.com/mbates/clover/blob/47134c1c76b78e8d968091d72c7813c85f9ad6d2/src/core/utils.ts#L23)

Convert a major-unit amount to cents.

## Parameters

### amount

`number`

Major-unit amount (e.g. 10.50 dollars)

## Returns

`number`

Amount in cents (e.g. 1050)

## Example

```typescript
toCents(10.50); // 1050
```
