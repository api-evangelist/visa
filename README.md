# Visa

Visa is a global payment technology company that facilitates electronic funds transfers by providing consumers, businesses, and governments with secure, convenient, and reliable payment solutions. Through its network of financial institutions and partners, Visa enables individuals to make purchases, transfer money, and access other financial services in over 200 countries and territories worldwide.

**Developer Portal:** https://developer.visa.com/  
**API Browser:** https://developer.visa.com/apibrowser  
**Getting Started:** https://developer.visa.com/capabilities/vdp-pilot-program/docs

## OpenAPI Specifications

| API | File |
|-----|------|
| B2B Virtual Account Payment Method | [openapi/b2b-virtual-account-payment-method.yml](openapi/b2b-virtual-account-payment-method.yml) |
| Card on File Data Inquiry | [openapi/card-on-file-data-inquiry.yml](openapi/card-on-file-data-inquiry.yml) |
| Foreign Exchange Rates | [openapi/foreign-exchange.yml](openapi/foreign-exchange.yml) |
| Payment Account Attributes Inquiry | [openapi/payment-account-attributes-inquiry.yml](openapi/payment-account-attributes-inquiry.yml) |
| Payment Account Validation | [openapi/payment-account-validation.yml](openapi/payment-account-validation.yml) |
| VCA Data Exchange | [openapi/vca-data-exchange.yml](openapi/vca-data-exchange.yml) |
| Visa Account Updater | [openapi/visa-account-updater.yml](openapi/visa-account-updater.yml) |
| Visa B2B Connect | [openapi/visa-b2b-connect.yml](openapi/visa-b2b-connect.yml) |
| Visa BIN Attribute Sharing | [openapi/visa-bin-attribute-sharing.yml](openapi/visa-bin-attribute-sharing.yml) |
| Visa Business Data Solutions | [openapi/visa-business-data-solutions.yml](openapi/visa-business-data-solutions.yml) |
| Visa Card Program Management | [openapi/visa-card-program-management.yml](openapi/visa-card-program-management.yml) |
| Visa Click to Pay | [openapi/visa-click-to-pay.yml](openapi/visa-click-to-pay.yml) |
| Visa Consent Management Service | [openapi/visa-consent-management-service.yml](openapi/visa-consent-management-service.yml) |
| Visa Data Tokens | [openapi/visa-data-tokens.yml](openapi/visa-data-tokens.yml) |
| Visa Digital Enablement | [openapi/visa-digital-enablement.yml](openapi/visa-digital-enablement.yml) |
| Visa Direct | [openapi/visa-direct.yml](openapi/visa-direct.yml) |
| Visa Global ATM Locator | [openapi/visa-global-atm-locator.yml](openapi/visa-global-atm-locator.yml) |
| Visa Government Insights Hub | [openapi/visa-government-insights-hub.yml](openapi/visa-government-insights-hub.yml) |
| Visa In-App Provisioning | [openapi/visa-in-app-provisioning.yml](openapi/visa-in-app-provisioning.yml) |
| Visa Merchant Offers | [openapi/visa-merchant-offers.yml](openapi/visa-merchant-offers.yml) |
| Visa Merchant Screening | [openapi/visa-merchant-screening.yml](openapi/visa-merchant-screening.yml) |
| Visa Merchant Search | [openapi/visa-merchant-search.yml](openapi/visa-merchant-search.yml) |
| Visa Payment Account Reference Inquiry | [openapi/visa-payment-account-reference-inquiry.yml](openapi/visa-payment-account-reference-inquiry.yml) |
| Visa Pilot Program Enablement | [openapi/visa-pilot-program-enablement.yml](openapi/visa-pilot-program-enablement.yml) |
| Visa Practical Money Skills | [openapi/visa-practical-money-skills-financial-education-platform.yml](openapi/visa-practical-money-skills-financial-education-platform.yml) |
| Visa Supplier Matching Service | [openapi/visa-supplier-matching-service.yml](openapi/visa-supplier-matching-service.yml) |
| Visa Transaction Controls | [openapi/visa-transaction-controls.yml](openapi/visa-transaction-controls.yml) |
| Visa Underwriting Intelligence Solutions | [openapi/visa-underwriting-intelligence-solutions.yml](openapi/visa-underwriting-intelligence-solutions.yml) |

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/visa-direct.yaml](capabilities/shared/visa-direct.yaml) | Visa Direct push/pull funds transfer |
| [capabilities/shared/visa-merchant-search.yaml](capabilities/shared/visa-merchant-search.yaml) | Merchant search, nearby merchants, and transaction enrichment |
| [capabilities/shared/foreign-exchange.yaml](capabilities/shared/foreign-exchange.yaml) | Foreign exchange rate lookup |
| [capabilities/shared/payment-account-validation.yaml](capabilities/shared/payment-account-validation.yaml) | Card account validation (AVS, CVV2, ANI) |
| [capabilities/shared/visa-transaction-controls.yaml](capabilities/shared/visa-transaction-controls.yaml) | Transaction controls and alerts |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [capabilities/money-movement.yaml](capabilities/money-movement.yaml) | Real-time transfers and foreign exchange (Visa Direct + FX) |
| [capabilities/merchant-intelligence.yaml](capabilities/merchant-intelligence.yaml) | Merchant data enrichment and location discovery |
| [capabilities/account-management.yaml](capabilities/account-management.yaml) | Account validation and transaction controls |

## JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/visa-payment-transaction-schema.json](json-schema/visa-payment-transaction-schema.json) | Payment transaction schema |
| [json-schema/visa-merchant-schema.json](json-schema/visa-merchant-schema.json) | Merchant entity schema |
| [json-schema/visa-account-schema.json](json-schema/visa-account-schema.json) | Account schema |

## JSON Structure

| File | Description |
|------|-------------|
| [json-structure/visa-payment-transaction-structure.json](json-structure/visa-payment-transaction-structure.json) | Payment transaction structure |
| [json-structure/visa-merchant-structure.json](json-structure/visa-merchant-structure.json) | Merchant entity structure |

## JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/visa-context.jsonld](json-ld/visa-context.jsonld) | Linked data context for Visa concepts |

## Examples

| File | Description |
|------|-------------|
| [examples/visa-direct-push-funds-example.json](examples/visa-direct-push-funds-example.json) | Push funds via Visa Direct |
| [examples/visa-merchant-search-example.json](examples/visa-merchant-search-example.json) | Search for merchants |
| [examples/visa-foreign-exchange-rates-example.json](examples/visa-foreign-exchange-rates-example.json) | Get FX rates |
| [examples/visa-payment-account-validation-example.json](examples/visa-payment-account-validation-example.json) | Validate a card account |
| [examples/visa-transaction-controls-example.json](examples/visa-transaction-controls-example.json) | Set transaction controls |
| [examples/visa-global-atm-locator-example.json](examples/visa-global-atm-locator-example.json) | Find nearby ATMs |

## Rules

| File | Description |
|------|-------------|
| [rules/visa-rules.yml](rules/visa-rules.yml) | Spectral ruleset for Visa API conventions |

## Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/visa-vocabulary.yml](vocabulary/visa-vocabulary.yml) | Domain vocabulary for Visa payment concepts |

## Tags

Accounts, Banking, Credit Cards, Digital Commerce, Digital Wallets, Fintech, Foreign Exchange, Fraud Prevention, Merchants, Money Movement, Payments, Tokenization

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
