# Class: WalletProvider

## Constructors

### new WalletProvider()

> **new WalletProvider**(`connection`, `walletPublicKey`): [`WalletProvider`](WalletProvider.md)

#### Parameters

• **connection**: `Connection`

• **walletPublicKey**: `PublicKey`

#### Returns

[`WalletProvider`](WalletProvider.md)

#### Defined in

[core/src/providers/wallet.ts:53](https://github.com/ai16z/eliza/blob/d62ba1b3bd238d14ac669409dda20e8446e34da9/core/src/providers/wallet.ts#L53)

## Methods

### fetchPortfolioValue()

> **fetchPortfolioValue**(`runtime`): `Promise`\<`WalletPortfolio`\>

#### Parameters

• **runtime**: `any`

#### Returns

`Promise`\<`WalletPortfolio`\>

#### Defined in

[core/src/providers/wallet.ts:105](https://github.com/ai16z/eliza/blob/d62ba1b3bd238d14ac669409dda20e8446e34da9/core/src/providers/wallet.ts#L105)

---

### fetchPrices()

> **fetchPrices**(`runtime`): `Promise`\<`Prices`\>

#### Parameters

• **runtime**: `any`

#### Returns

`Promise`\<`Prices`\>

#### Defined in

[core/src/providers/wallet.ts:150](https://github.com/ai16z/eliza/blob/d62ba1b3bd238d14ac669409dda20e8446e34da9/core/src/providers/wallet.ts#L150)

---

### formatPortfolio()

> **formatPortfolio**(`runtime`, `portfolio`, `prices`): `string`

#### Parameters

• **runtime**: `any`

• **portfolio**: `WalletPortfolio`

• **prices**: `Prices`

#### Returns

`string`

#### Defined in

[core/src/providers/wallet.ts:192](https://github.com/ai16z/eliza/blob/d62ba1b3bd238d14ac669409dda20e8446e34da9/core/src/providers/wallet.ts#L192)

---

### getFormattedPortfolio()

> **getFormattedPortfolio**(`runtime`): `Promise`\<`string`\>

#### Parameters

• **runtime**: `any`

#### Returns

`Promise`\<`string`\>

#### Defined in

[core/src/providers/wallet.ts:229](https://github.com/ai16z/eliza/blob/d62ba1b3bd238d14ac669409dda20e8446e34da9/core/src/providers/wallet.ts#L229)
