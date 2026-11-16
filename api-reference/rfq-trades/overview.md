# Overview

> Explore the RFQ Trades Partner API for settling trades matched on your platform.

## APIs

The RFQ Trades Partner API settles trades that your platform matched off
Polymarket, over HTTP for requests and over WebSocket for trade status. Access
is by invitation: see the [Institutional Overview](../../partners/overview.md) for who
it is for and how to request access.

> [card] HTTP API
>
> `https://external-rfq-partner.polymarket.com`
>
> Validate, prepare, submit, and read RFQ trades.

> [card] WebSocket API
>
> `wss://external-rfq-partner.polymarket.com/v1/ws/rfq-trades`
>
> Stream your trades' status changes.

The testing environment's base URL is shared during onboarding, together with
test API keys for that environment.

## Before You Integrate

> [card] [Authentication](./authentication.md)
>
> Sign every request with your partner API key.

> [card] [Trade Flow](../../partners/rfq-trades.md)
>
> Find a market, then validate, sign, submit, and track a trade.

> [card] [Errors](../../partners/rfq-trades.md#errors)
>
> Read the error envelope and every rejection reason.


This documentation is built and hosted on [Mintlify](https://mintlify.com), a developer documentation platform.