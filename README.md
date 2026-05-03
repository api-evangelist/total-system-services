# Total System Services (TSYS)

Total System Services (TSYS) was a leading global payment solutions provider offering payment processing services to financial and nonfinancial institutions before merging with Global Payments in 2019. TSYS provides an end-to-end payment stack spanning payment gateway services for merchants, card issuing for banks and fintechs, merchant acquiring, virtual card programs, and comprehensive reporting. The TSYS developer portal provides APIs for transaction processing, cardholder management, merchant services, and commercial virtual solutions.

**Website:** [https://www.tsys.com/](https://www.tsys.com/)
**Developer Portal:** [https://developers.tsys.com/](https://developers.tsys.com/)
**Merchant Documentation:** [https://docs.tsysmerchant.com/](https://docs.tsysmerchant.com/)

---

## APIs

### TSYS Payment Gateway

API for processing credit, debit, and prepaid card transactions. Supports authorization, capture, void, refund, and batch settlement operations for card-present and card-not-present scenarios.

- **Documentation:** [https://developers.tsys.com/](https://developers.tsys.com/)
- **OpenAPI Spec:** [openapi/tsys-payment-gateway-openapi.yml](openapi/tsys-payment-gateway-openapi.yml)

### TSYS Issuing Platform

API-driven card issuing platform for financial institutions and fintechs to manage card programs, cardholder accounts, spending controls, and dispute management.

- **Documentation:** [https://www.tsys.com/platform](https://www.tsys.com/platform)
- **OpenAPI Spec:** [openapi/tsys-issuing-openapi.yml](openapi/tsys-issuing-openapi.yml)

### TSYS Merchant Services

Merchant boarding, account management, reporting, and settlement services for acquirers and payment facilitators.

- **Documentation:** [https://docs.tsysmerchant.com/](https://docs.tsysmerchant.com/)

---

## Artifacts

### OpenAPI Specifications

| File | API | Description |
|---|---|---|
| [tsys-payment-gateway-openapi.yml](openapi/tsys-payment-gateway-openapi.yml) | Payment Gateway | Merchant transaction processing |
| [tsys-issuing-openapi.yml](openapi/tsys-issuing-openapi.yml) | Issuing Platform | Card program and cardholder management |

### Naftiko Capabilities

**Workflow Capabilities:**

| File | Description |
|---|---|
| [capabilities/payment-processing.yaml](capabilities/payment-processing.yaml) | Merchant payment acceptance workflow (7 tools) |
| [capabilities/card-issuing.yaml](capabilities/card-issuing.yaml) | Card program and cardholder management workflow (9 tools) |

**Shared Per-API Definitions:**

| File | API |
|---|---|
| [capabilities/shared/payment-gateway.yaml](capabilities/shared/payment-gateway.yaml) | TSYS Payment Gateway |
| [capabilities/shared/issuing-platform.yaml](capabilities/shared/issuing-platform.yaml) | TSYS Issuing Platform |

### JSON Schemas

| File | Resource |
|---|---|
| [json-schema/tsys-transaction-schema.json](json-schema/tsys-transaction-schema.json) | Transaction |

### JSON Structure

| File | Resource |
|---|---|
| [json-structure/tsys-transaction-structure.json](json-structure/tsys-transaction-structure.json) | Transaction |

### JSON-LD Context

| File | Description |
|---|---|
| [json-ld/total-system-services-context.jsonld](json-ld/total-system-services-context.jsonld) | Linked data context for TSYS payment resources |

### Examples

| File | Operation |
|---|---|
| [examples/tsys-process-sale-example.json](examples/tsys-process-sale-example.json) | Process Sale |

### Spectral Rules

| File | Description |
|---|---|
| [rules/tsys-spectral-rules.yml](rules/tsys-spectral-rules.yml) | API design rules for TSYS OpenAPI specifications |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/total-system-services-vocabulary.yml](vocabulary/total-system-services-vocabulary.yml) | Payment processing vocabulary for TSYS APIs |

---

## Tags

`Payments` `Payment Processing` `Card Issuing` `Merchant Services` `Fintech` `Financial Services`
