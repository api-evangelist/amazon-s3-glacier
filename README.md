# Amazon S3 Glacier
Amazon S3 Glacier is a secure, durable, and extremely low-cost Amazon S3 storage class purpose-built for long-term data archiving and digital preservation. It provides comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements, with retrieval options ranging from minutes to hours depending on your access needs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Archive, AWS, Backup, Storage

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon S3 Glacier API
The Amazon S3 Glacier API provides programmatic access to manage long-term archive storage. It enables developers to create and manage vaults, upload and retrieve archives, configure vault notifications and access policies, initiate inventory retrieval jobs, and manage data lifecycle for cost- effective archival storage.

**Human URL:** [https://aws.amazon.com/s3/storage-classes/glacier/](https://aws.amazon.com/s3/storage-classes/glacier/)

#### Tags:

 - Archive, AWS, Backup, Storage

#### Properties

- [Documentation](https://docs.aws.amazon.com/amazonglacier/)
- [OpenAPI](openapi/amazon-s3-glacier-openapi.yml)
- [Pricing](https://aws.amazon.com/s3/pricing/)
- [GettingStarted](https://aws.amazon.com/s3/getting-started/)
- [FAQ](https://aws.amazon.com/s3/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Portal](https://aws.amazon.com/s3/storage-classes/glacier/)
- [Documentation](https://docs.aws.amazon.com/amazonglacier/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHubOrganization](https://github.com/aws)
- [Portal](https://console.aws.amazon.com/glacier/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [JSON-LD](json-ld/amazon-s3-glacier-api-describe-vault-context.jsonld)
- [JSON-LD](json-ld/amazon-s3-glacier-api-job-parameters-context.jsonld)
- [JSON-LD](json-ld/amazon-s3-glacier-api-list-vaults-context.jsonld)
- [JSON-LD](json-ld/amazon-s3-glacier-context.jsonld)
- [JSON-LD](json-ld/amazon-s3-glacier-vault-context.jsonld)
- [JSONSchema](json-schema/amazon-s3-glacier-api-describe-vault-output-schema.json)
- [JSONSchema](json-schema/amazon-s3-glacier-api-job-parameters-schema.json)
- [JSONSchema](json-schema/amazon-s3-glacier-api-list-vaults-output-schema.json)
- [JSONSchema](json-schema/amazon-s3-glacier-vault-schema.json)
- [JSONStructure](json-structure/amazon-s3-glacier-api-describe-vault-output-structure.json)
- [JSONStructure](json-structure/amazon-s3-glacier-api-job-parameters-structure.json)
- [JSONStructure](json-structure/amazon-s3-glacier-api-list-vaults-output-structure.json)
- [JSONStructure](json-structure/amazon-s3-glacier-vault-structure.json)
- [Example](examples/amazon-s3-glacier-api-describe-vault-output-example.json)
- [Example](examples/amazon-s3-glacier-api-job-parameters-example.json)
- [Example](examples/amazon-s3-glacier-api-list-vaults-output-example.json)
- [Example](examples/amazon-s3-glacier-vault-example.json)
- [NaftikoCapability](capabilities/amazon-s3-glacier.yaml)
- [NaftikoCapability](capabilities/shared/amazon-s3-glacier.yaml)
- [SpectralRules](rules/amazon-s3-glacier-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-s3-glacier-vocabulary.yaml)
- [OpenAPI](openapi/amazon-s3-glacier-api-openapi.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-s3-glacier-api-openapi.yml](openapi/amazon-s3-glacier-api-openapi.yml)

### JSON Schema

- [amazon-s3-glacier-api-describe-vault-output-schema.json](json-schema/amazon-s3-glacier-api-describe-vault-output-schema.json)
- [amazon-s3-glacier-api-job-parameters-schema.json](json-schema/amazon-s3-glacier-api-job-parameters-schema.json)
- [amazon-s3-glacier-api-list-vaults-output-schema.json](json-schema/amazon-s3-glacier-api-list-vaults-output-schema.json)
- [amazon-s3-glacier-vault-schema.json](json-schema/amazon-s3-glacier-vault-schema.json)

### JSON Structure

- [amazon-s3-glacier-api-describe-vault-output-structure.json](json-structure/amazon-s3-glacier-api-describe-vault-output-structure.json)
- [amazon-s3-glacier-api-job-parameters-structure.json](json-structure/amazon-s3-glacier-api-job-parameters-structure.json)
- [amazon-s3-glacier-api-list-vaults-output-structure.json](json-structure/amazon-s3-glacier-api-list-vaults-output-structure.json)
- [amazon-s3-glacier-vault-structure.json](json-structure/amazon-s3-glacier-vault-structure.json)

### JSON-LD

- [amazon-s3-glacier-api-describe-vault-context.jsonld](json-ld/amazon-s3-glacier-api-describe-vault-context.jsonld)
- [amazon-s3-glacier-api-job-parameters-context.jsonld](json-ld/amazon-s3-glacier-api-job-parameters-context.jsonld)
- [amazon-s3-glacier-api-list-vaults-context.jsonld](json-ld/amazon-s3-glacier-api-list-vaults-context.jsonld)
- [amazon-s3-glacier-context.jsonld](json-ld/amazon-s3-glacier-context.jsonld)
- [amazon-s3-glacier-vault-context.jsonld](json-ld/amazon-s3-glacier-vault-context.jsonld)

### Examples

- [amazon-s3-glacier-api-describe-vault-output-example.json](examples/amazon-s3-glacier-api-describe-vault-output-example.json)
- [amazon-s3-glacier-api-job-parameters-example.json](examples/amazon-s3-glacier-api-job-parameters-example.json)
- [amazon-s3-glacier-api-list-vaults-output-example.json](examples/amazon-s3-glacier-api-list-vaults-output-example.json)
- [amazon-s3-glacier-vault-example.json](examples/amazon-s3-glacier-vault-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [amazon-s3-glacier.yaml](capabilities/shared/amazon-s3-glacier.yaml)

### Workflow Capabilities

- [amazon-s3-glacier.yaml](capabilities/amazon-s3-glacier.yaml)

## Vocabulary

- [amazon-s3-glacier-vocabulary.yaml](vocabulary/amazon-s3-glacier-vocabulary.yaml)

## Rules

- [amazon-s3-glacier-spectral-rules.yml](rules/amazon-s3-glacier-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

