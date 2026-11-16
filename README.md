# Vultr Crypto Payment: How to Top Up With Bitcoin or USDC, Which Coins BitPay Accepts, and Where the $300 Credit Fits

Vultr accepts cryptocurrency, and BitPay processes the transaction. You fund the account from the console: **Account → Make a Payment** under **BILLING**, then select **Crypto**, choose a preset amount or click **Other** to type your own. The coins land in your Vultr account balance, and that balance is what keeps every instance you run online.

Two details are missing from Vultr's own documentation, and they matter before you send funds. The payment doc stops at "select Crypto" and publishes no minimum, no processing fee, and no settlement time. Separately, the coin list circulating in help articles is older than the payment page itself. Both gaps are addressed below, along with which plan to fund first and how the $300 new-customer code fits in.

> **Quick answer:** Vultr takes Bitcoin, Ethereum, Litecoin, USDC and several other coins through BitPay, with no card involved. It suits anyone already holding crypto who would rather not keep a card on file with a cloud provider. 👉 [Open a Vultr account and check current plan pricing](https://bit.ly/VuLtr)

## Vultr's compute plans and what each one costs

Vultr sells compute in four families. Within each family the price moves with vCPU count, RAM, storage and region, so the figures below are the lowest published configuration, not a fixed menu.

| Plan family | Built for | Entry price | Billing | Current pricing |
| --- | --- | --- | --- | --- |
| Cloud Compute | Shared vCPU instances, including high-frequency and high-performance variants; the usual pick for web apps, bots and test boxes | from $2.50/mo | Hourly, no contract | [Cloud Compute pricing](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Optimized Cloud Compute | Dedicated vCPU, split into general purpose, CPU-optimized, memory-optimized and storage-optimized shapes | from about $28/mo | Hourly, no contract | [Optimized Cloud Compute pricing](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Bare Metal | Single-tenant hardware with no hypervisor layer, for workloads that need the whole machine | from about $120/mo | Hourly, no contract | [Bare Metal pricing](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU | GPU instances for model training, inference and rendering | from about $90/mo | Hourly, no contract | [Cloud GPU pricing](https://www.vultr.com/pricing/?ref=9738262-9J) |

Kubernetes Engine, managed databases, block storage and object storage are billed in addition to the instance itself, so a $2.50 Cloud Compute box with a managed database attached costs considerably more than $2.50. Whatever you pick, the instance draws from your account balance. A deposit made today determines how many days a server keeps running, and Vultr is explicit about the consequence of letting that balance fall short: services can be suspended, data can be lost, and bills can go overdue.

## How to pay Vultr with crypto, step by step

The flow lives entirely inside the Vultr console. There is no separate crypto portal to sign into.

1. Sign in and open **Account**, then select **Make a Payment** under **BILLING**.
2. Select **Crypto**. On some screens and in BitPay's own merchant directory this option is labelled **BitPay** instead.
3. Pick one of the preset amounts, or click **Other** and enter a custom figure. Nothing forces you into fixed tiers, so a $12 top-up works the same way as a $500 one.
4. Complete the transfer in the BitPay checkout using a supported wallet. BitPay states that payments go directly from your wallet, and that Vultr accepts crypto from over 100 different wallets.

Vultr's documentation doesn't state a minimum deposit, a processing fee, or how long the balance takes to appear. The checkout screen shows the exact amount owed, and that figure is the one to trust. If you need a guaranteed arrival window for a specific payment, treat the absence of published terms as a reason to top up before an existing server is close to running dry rather than after.

👉 [Create a Vultr account to reach the billing page](https://bit.ly/VuLtr)

## Which coins BitPay accepts for Vultr

Vultr's help documentation has listed nine digital currencies for BitPay payments. The most recent version of that list dates to September 2025, and the October 2026 rewrite of the payments page dropped the coin table entirely, so treat this as the documented set rather than a live confirmation.

| Coin | Ticker |
| --- | --- |
| Bitcoin | BTC |
| Bitcoin Cash | BCH |
| Ethereum | ETH |
| Litecoin | LTC |
| Dogecoin | DOGE |
| USD Coin | USDC |
| Paxos Standard | PAX |
| Binance USD | BUSD |
| Gemini Dollar | GUSD |

The checkout page decides what you can actually pay with. BitPay adjusts supported assets over time, and a coin that appears above may be missing from the selection screen for reasons Vultr doesn't publish. Open the BitPay step first and confirm your coin is there before you move funds off an exchange.

Wallets are the other half of the equation. BitPay names Exodus, MetaMask, Electrum, Trust and Coinbase among the wallets it supports for Vultr payments, and the "over 100 wallets" figure covers hardware wallets, browser extensions and exchange-hosted balances alike.

## Crypto next to the other five payment methods

Vultr lists six ways to fund an account. Crypto is the only one that doesn't route through a card network, a bank or a stored-value code.

| Method | What you need | Worth knowing |
| --- | --- | --- |
| Credit Card | Name, billing address, card details | Visa, Mastercard, American Express, Discover and JCB are accepted |
| PayPal | A PayPal balance or linked funding source | Region-dependent extras include Giropay and bank transfers |
| Crypto | A wallet plus a BitPay-supported coin | No card; minimum, fee and settlement time are unpublished |
| Alipay | An Alipay account | Preset amounts or a custom figure, same as crypto |
| Wire Transfer | Bank details | You keep the confirmation number for future reference |
| Gift Code | A valid code | Confirm Vultr accepts the code on your account before assuming it applied |

The trade-off is straightforward. Crypto removes the card network and the bank from the loop, which is the whole point for people who don't want a payment card tied to a cloud account. In exchange you take on two unknowns Vultr doesn't document: how small a deposit is allowed, and what the processor charges on top. Cards and PayPal carry their own limits, but at least the fee structure is familiar.

## Three things that catch people out

**The button may not say "Crypto."** Vultr's own docs call it Crypto, while BitPay's merchant directory tells shoppers to choose "BitPay" as the payment method. Same channel, two labels. If you can't find a Crypto option, look for BitPay before concluding the account isn't eligible.

**You are funding a balance, not paying a bill.** Vultr's billing page tops up the account as a whole. Individual servers don't get individual invoices you can settle with a wallet transfer. This matters when a project runs several instances: a single top-up covers all of them, and a balance that looks healthy can drain faster than expected once you add a second machine.

**The coin list is a snapshot.** The nine currencies above come from Vultr's help documentation, last seen in September 2025. The current payments page, updated in October 2026, describes how to pay but no longer lists assets. Any article stating the list as current fact is repeating older material, including this one, which is why the checkout screen gets the final say.

## The $300 code and how promo credit sits alongside a crypto top-up

Vultr's own coupons page lists four new-customer offers, and the $300 one is real:

- **FLY300VULTR** — $300 free credit, new customers only, select products only, cannot be combined with other offers.
- **FLYTWOHUNDRED** — $200 free credit, same conditions.
- **250VULTRFLY** — $250 free credit, same conditions.
- **VULTRMATCH** — Vultr matches your first deposit dollar for dollar, up to $100.

The published terms for these codes say nothing about payment method. They restrict eligibility to genuinely new customers, limit the credit to selected products, and block stacking with other offers. What that means in practice: paying by crypto doesn't disqualify you on the wording, but the credit also isn't a discount on your deposit. It's promotional balance that gets consumed as you use eligible services.

Two practical notes. Promo credit expires, and the VULTRMATCH terms put its match credit at 12 months, so activate a code when you're ready to deploy rather than weeks ahead. And expect to add a payment method before any credit becomes usable, which for crypto means a small initial deposit rather than a $0 card verification.

👉 [Check the current Vultr coupon codes and their terms](https://www.vultr.com/coupons?ref=9738262-9J)

## FAQ

**Does Vultr accept Bitcoin?** Yes. Bitcoin is the longest-standing coin on Vultr's documented BitPay list, and payments are made directly from your wallet to the BitPay checkout.

**Can I pay Vultr with USDC?** USDC appears on the documented list of nine coins. Confirm it's selectable at checkout, since BitPay's supported assets change and Vultr no longer publishes a coin table on its payment page.

**Is there a minimum crypto top-up?** Vultr doesn't publish one. The custom **Other** amount field suggests you aren't restricted to preset tiers, but the checkout is the only place that shows the accepted figure.

**Can I use the $300 credit if I pay with crypto?** The code's terms restrict it to new customers, selected products and no stacking. Payment method isn't listed as a condition, and the credit applies to usage rather than to your deposit.

## Which plan to fund first

One small project, a bot or a staging box: the entry Cloud Compute instance at $2.50/mo, topped up in a small amount and refilled when the balance dips. There's no advantage to parking $200 in an account for a single $2.50 server, and hourly billing means you can destroy and rebuild without wasting a prepaid month.

Several projects, a team, or anything with a managed database attached: a higher Cloud Compute or Optimized Cloud Compute shape, funded in one larger top-up. Each crypto transfer is a separate checkout, so consolidating into fewer, bigger deposits cuts the number of times you repeat the process.

Before you send anything, confirm two things on screen: that your coin is selectable in the BitPay step, and that any promo code you plan to use has been applied to the account rather than assumed. Then fund the balance and deploy.

👉 [Start with Vultr and fund your account by crypto](https://bit.ly/VuLtr)
