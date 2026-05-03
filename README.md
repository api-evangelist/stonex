# StoneX

StoneX Group is a global financial services organization that provides execution, risk management, market intelligence, and post-trade services across asset classes and markets to institutional, commercial, and retail clients. StoneX offers REST APIs for payments, clearing, and futures trading with OAuth 2.0 authentication.

**URL:** [https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stonex/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Fortune 500:** Yes

## Tags

- Finance
- Financial Services
- Payments
- Clearing
- Futures
- Trading
- Risk Management

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### StoneX Payments API

Cross-border payment processing in 140+ currencies with local currency acceptance and global settlement.

**Human URL:** [https://docs.payments.stonex.io/](https://docs.payments.stonex.io/)

### StoneX Clearing API

Institutional clearing accounts, trade submission, position tracking, and document management.

**Human URL:** [https://docs.clearing.stonex.com/](https://docs.clearing.stonex.com/)

### StoneX GF Futures API

Institutional-grade futures trading with market data, order management, and account tracking.

**Human URL:** [https://futures-media.stonex.com/gfapi/index.html](https://futures-media.stonex.com/gfapi/index.html)

### StoneX Developer Portal

Full API product catalog with subscription keys and documentation.

**Human URL:** [https://developer.stonex.com/](https://developer.stonex.com/)

## OpenAPI Specifications

| Spec | Operations | Description |
|---|---|---|
| [stonex-payments-openapi.yml](openapi/stonex-payments-openapi.yml) | 5 | StoneX Payments REST API — payments and FX rates |
| [stonex-clearing-openapi.yml](openapi/stonex-clearing-openapi.yml) | 9 | StoneX Clearing REST API — accounts, trades, and documents |

## Capabilities

### Workflow Capabilities

| Capability | Tools | Description |
|---|---|---|
| [financial-services.yaml](capabilities/financial-services.yaml) | 10 | Unified financial services — payments, FX, clearing, trading |

### Shared Definitions

| Definition | Resources | Description |
|---|---|---|
| [shared/stonex-payments.yaml](capabilities/shared/stonex-payments.yaml) | 4 | StoneX Payments API consumed definition |
| [shared/stonex-clearing.yaml](capabilities/shared/stonex-clearing.yaml) | 6 | StoneX Clearing API consumed definition |

## Rules

| Ruleset | Description |
|---|---|
| [stonex-rules.yml](rules/stonex-rules.yml) | Spectral ruleset enforcing StoneX API conventions |

## JSON Schema

| Schema | Description |
|---|---|
| [stonex-payment-schema.json](json-schema/stonex-payment-schema.json) | Cross-border payment schema |
| [stonex-clearing-account-schema.json](json-schema/stonex-clearing-account-schema.json) | Institutional clearing account schema |

## JSON Structure

| Structure | Description |
|---|---|
| [stonex-payment-structure.json](json-structure/stonex-payment-structure.json) | Payment response document structure |

## JSON-LD

| Context | Description |
|---|---|
| [stonex-context.jsonld](json-ld/stonex-context.jsonld) | JSON-LD context mapping StoneX vocabulary to schema.org and FIBO |

## Examples

| Example | Description |
|---|---|
| [stonex-create-payment-example.json](examples/stonex-create-payment-example.json) | Create a USD to EUR cross-border payment |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [stonex-vocabulary.yml](vocabulary/stonex-vocabulary.yml) | Domain vocabulary for FX payments, clearing, and institutional trading |

## GitHub Organizations

- [github.com/StoneXLabs](https://github.com/StoneXLabs) — C++ AMQP client libraries, data engineering tools

## Common Properties

- [Website](https://www.stonex.com)
- [Developer Portal](https://developer.stonex.com/)
- [Documentation](https://developer.stonex.com/documentation)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
