# Telefono

Telefono is a phone number intelligence and validation API platform providing real-time phone number lookup, validation, carrier information, line type detection, and number formatting services. The platform helps businesses verify user phone numbers, detect fraud, improve SMS deliverability, and enrich contact data.

**Human URL:** [https://www.telefono.com](https://www.telefono.com)
**Developer URL:** [https://developers.telefono.com](https://developers.telefono.com)

## APIs

### Telefono Phone Validation API
Validate phone numbers in real-time to determine validity, line type, reachability, carrier, and country.

- **Documentation:** [https://developers.telefono.com/validation](https://developers.telefono.com/validation)
- **OpenAPI Spec:** [openapi/telefono-validation-openapi.yml](openapi/telefono-validation-openapi.yml)

### Telefono Carrier Lookup API
Look up carrier information, MCC/MNC, network type, and portability status for any phone number.

- **Documentation:** [https://developers.telefono.com/carrier](https://developers.telefono.com/carrier)
- **OpenAPI Spec:** [openapi/telefono-carrier-openapi.yml](openapi/telefono-carrier-openapi.yml)

### Telefono Number Formatting API
Format phone numbers between E.164, national, international, and RFC3966 formats.

- **Documentation:** [https://developers.telefono.com/format](https://developers.telefono.com/format)
- **OpenAPI Spec:** [openapi/telefono-format-openapi.yml](openapi/telefono-format-openapi.yml)

## Artifacts

### OpenAPI Specifications
| File | Description |
|---|---|
| [openapi/telefono-validation-openapi.yml](openapi/telefono-validation-openapi.yml) | Phone Validation API — single and batch validation |
| [openapi/telefono-carrier-openapi.yml](openapi/telefono-carrier-openapi.yml) | Carrier Lookup API — MCC/MNC, network type, portability |
| [openapi/telefono-format-openapi.yml](openapi/telefono-format-openapi.yml) | Number Formatting API — E.164, national, international, RFC3966 |

### JSON Schemas
| File | Description |
|---|---|
| [json-schema/telefono-validation-result-schema.json](json-schema/telefono-validation-result-schema.json) | Validation result JSON Schema |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/telefono-validation-result-structure.json](json-structure/telefono-validation-result-structure.json) | Validation result field structure |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/telefono-context.jsonld](json-ld/telefono-context.jsonld) | JSON-LD context for Telefono data types |

### Examples
| File | Description |
|---|---|
| [examples/telefono-validate-number-example.json](examples/telefono-validate-number-example.json) | Phone number validation example |
| [examples/telefono-carrier-lookup-example.json](examples/telefono-carrier-lookup-example.json) | Carrier lookup example |

### Spectral Rules
| File | Description |
|---|---|
| [rules/telefono-rules.yml](rules/telefono-rules.yml) | Spectral ruleset for Telefono API conventions |

### Naftiko Capabilities
| File | Description |
|---|---|
| [capabilities/shared/telefono-validation.yaml](capabilities/shared/telefono-validation.yaml) | Shared phone intelligence capability definition |
| [capabilities/phone-intelligence.yaml](capabilities/phone-intelligence.yaml) | Phone intelligence workflow (REST port 8080, MCP port 9090) |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/telefono-vocabulary.yml](vocabulary/telefono-vocabulary.yml) | Telefono platform vocabulary |

## Common Properties

| Property | URL |
|---|---|
| Authentication | https://developers.telefono.com/authentication |
| Rate Limits | https://developers.telefono.com/rate-limits |
| Pricing | https://www.telefono.com/pricing |
| Terms of Service | https://www.telefono.com/terms |
| Privacy Policy | https://www.telefono.com/privacy |
| Status | https://status.telefono.com |
| Support | https://www.telefono.com/support |

## Maintainers
- **Telefono Team** — api@telefono.com
