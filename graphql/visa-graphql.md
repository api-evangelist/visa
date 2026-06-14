# Visa GraphQL Schema

## Overview

Visa does not offer a native public GraphQL API. The Visa Developer Platform exposes its capabilities through REST APIs secured via mutual TLS (mTLS) and OAuth 2.0, available to certified partners and financial institutions through commercial agreements. This conceptual GraphQL schema is derived from the full breadth of Visa's documented REST API surface area, including Visa Direct, Visa Token Service, Foreign Exchange, Payment Account Validation, Merchant Search, Transaction Controls, Click to Pay, Installments, Loyalty/Offers, and BIN Attribute Sharing.

## Source APIs

- Visa Direct (Push/Pull Funds) — https://developer.visa.com/capabilities/visa_direct
- Payment Account Validation — https://developer.visa.com/capabilities/pav
- Payment Account Attributes Inquiry — https://developer.visa.com/capabilities/paai
- Foreign Exchange Rates — https://developer.visa.com/capabilities/foreign_exchange
- Visa Token Service — https://developer.visa.com/capabilities/vts
- Merchant Search — https://developer.visa.com/capabilities/merchant_search
- Visa Transaction Controls — https://developer.visa.com/capabilities/vctc
- Visa Click to Pay — https://developer.visa.com/capabilities/visa-secure-remote-commerce
- Installment Transaction Service — https://developer.visa.com/capabilities/installment-transaction-service
- Visa Merchant Offers (VMORC) — https://developer.visa.com/capabilities/vmorc
- Visa BIN Attribute Sharing Service — https://developer.visa.com/capabilities/visa-bin-attribute-sharing-service
- Visa Account Updater — https://developer.visa.com/capabilities/vau
- Visa Business Data Solutions — https://developer.visa.com/capabilities/vbds
- Visa Global ATM Locator — https://developer.visa.com/capabilities/atmlocator
- Visa Card Program Management — https://developer.visa.com/capabilities/vcpm
- Visa Consent Management Service — https://developer.visa.com/capabilities/vcms
- Visa Supplier Matching Service — https://developer.visa.com/capabilities/suppliermatchingservice
- Visa B2B Connect — https://developer.visa.com/capabilities/vba
- Visa Digital Enablement — https://developer.visa.com/capabilities/visa-digital-enablement-lite
- Visa In-App Provisioning — https://developer.visa.com/capabilities/visa-in-app-provisioning
- Card on File Data Inquiry — https://developer.visa.com/capabilities/card-on-file-data-inquiry

## Schema File

- [visa-schema.graphql](visa-schema.graphql)

## Type Summary (63 types)

| Domain | Types |
|---|---|
| Core Transactions | Transaction, Authorization, Capture, Settlement, Reversal, Refund |
| Cards & Accounts | Card, CardAccount, Cardholder, Account, Balance, BINAttributes |
| Money Movement | PushFunds, PullFunds, P2PTransfer, FundingInstruction, CashBack |
| Tokenization | Token, TokenRequest, TokenLifecycle, TokenCryptogram |
| Merchants | Merchant, MerchantLocation, MerchantCategory, MerchantOffer |
| Foreign Exchange | CurrencyConversion, FX, ExchangeRate, FXQuote |
| Risk & Fraud | DecisionManager, RiskScore, ThreeDS, ThreeDSResult, VIPAlert |
| Installments | Installment, InstallmentPlan, SplitPayment |
| Loyalty & Offers | LoyaltyProgram, Offer, Deal, BenefitProgram, RewardRedemption |
| Digital Payments | ClickToPayRequest, PaymentMethod, DigitalWallet, WalletToken |
| Payments Infrastructure | ATM, ATMLocation, VisaNet, VisaNetMessage |
| Platform | DirectAPI, PushNotification, PushToCard, AccountUpdate |
| Supporting | Address, PhoneNumber, Money, PageInfo |

## GitHub

- https://github.com/visa
