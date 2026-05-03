# United States Steel (united-states-steel)

United States Steel Corporation (U.S. Steel) is an integrated steel producer headquartered in Pittsburgh, Pennsylvania, with major production operations in the United States and Central Europe. The company serves customers in automotive, construction, container, energy, and industrial markets with advanced high-strength steels, coated products, hot-rolled and cold-rolled coils, electrical steel, and tubular products. U.S. Steel provides digital customer tools through the SteelTrack platform for order management, inventory tracking, shipment history, and certified test reporting.

**URL:** [Visit U.S. Steel](https://www.ussteel.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Steel, Manufacturing, Automotive, Construction, Energy, Supply Chain

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### U.S. Steel SteelTrack API

SteelTrack is U.S. Steel's internet-based customer platform providing order status reporting, inventory tracking, shipment history, material release, and physical and chemical test reporting. The API enables ERP and supply chain integration for steel order management and quality documentation.

**Human URL:** [https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel](https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel)

#### Tags:

 - Steel, Supply Chain, Order Management, Manufacturing

#### Properties

- [Documentation](https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel)
- [OpenAPI](openapi/united-states-steel-steeltrack-openapi.yml)
- [Order Schema](json-schema/steeltrack-order-schema.json)
- [Shipment Schema](json-schema/steeltrack-shipment-schema.json)
- [Order Structure](json-structure/steeltrack-order-structure.json)
- [JSON-LD Context](json-ld/united-states-steel-steeltrack-context.jsonld)
- [Order Example](examples/steeltrack-order-example.json)

## Common Properties

- [Website](https://www.ussteel.com)
- [Customer Solutions Portal](https://www.ussteel.com/customers/solutions)
- [Doing Business with U.S. Steel](https://www.ussteel.com/about-us/doing-business-with-u.-s.-steel)

## Features

| Name | Description |
|------|-------------|
| Order Status Reporting | Customizable reports on order availability and status across all U.S. Steel facilities. |
| Inventory Tracking | On-demand inventory reporting filterable by OP, customer, PO, and part number with flexible sorting. |
| Shipment History | Load history searchable by order item, part number, and PO with optional coil-level detail. |
| Certified Test Reports | Physical, mechanical, and chemical test reports with electronic certification signatures. |
| 24/7 Availability | SteelTrack platform operates 24 hours a day, 7 days a week with console dashboard and workflow guidance. |
| Multi-Facility Coverage | Consolidated view across all U.S. Steel production facilities including Gary Works, Mon Valley, and Big River Steel. |
| Real-Time Updates | New and updated test report information relayed throughout the day to the Test Reports System. |

## Use Cases

| Name | Description |
|------|-------------|
| ERP Integration | Integrate SteelTrack order and shipment data directly into customer ERP systems for automated procurement workflows. |
| Quality Documentation | Automate retrieval of certified mill test reports for compliance, quality audits, and material traceability. |
| Supply Chain Visibility | Track steel coil status from order placement through production and delivery for manufacturing planning. |
| Inventory Planning | Monitor available inventory and in-transit material to optimize material release and production scheduling. |
| Automotive Supplier Compliance | Access physical and chemical test data to meet automotive OEM supplier quality requirements (PPAP, IMDS). |
| Shipment Reconciliation | Reconcile received shipments against orders using coil-level shipping data for accounts payable processing. |

## Integrations

| Name | Description |
|------|-------------|
| SAP | SteelTrack data integrates with SAP ERP for automated purchase order management and goods receipt processing. |
| Oracle ERP | Order and inventory data connects to Oracle ERP Cloud for supply chain and procurement workflows. |
| EDI | Electronic Data Interchange for standard steel industry transaction sets including orders, shipment notices, and invoices. |
| Nippon Steel | Technology partnership with Nippon Steel Corporation following acquisition for shared manufacturing intelligence. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [U.S. Steel SteelTrack API](openapi/united-states-steel-steeltrack-openapi.yml)

### JSON Schema

- [steeltrack-order-schema.json](json-schema/steeltrack-order-schema.json)
- [steeltrack-order-list-schema.json](json-schema/steeltrack-order-list-schema.json)
- [steeltrack-inventory-item-schema.json](json-schema/steeltrack-inventory-item-schema.json)
- [steeltrack-shipment-schema.json](json-schema/steeltrack-shipment-schema.json)
- [steeltrack-test-report-schema.json](json-schema/steeltrack-test-report-schema.json)

### JSON Structure

- [steeltrack-order-structure.json](json-structure/steeltrack-order-structure.json)
- [steeltrack-shipment-structure.json](json-structure/steeltrack-shipment-structure.json)
- [steeltrack-test-report-structure.json](json-structure/steeltrack-test-report-structure.json)

### JSON-LD

- [SteelTrack Context](json-ld/united-states-steel-steeltrack-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [U.S. Steel SteelTrack API](capabilities/shared/steeltrack.yaml) — 5 operations for order, inventory, shipment, and test report management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Supply Chain Management](capabilities/supply-chain-management.yaml) | SteelTrack | 5 | Procurement Manager, Supply Chain Analyst, Quality Engineer |

## Vocabulary

- [United States Steel Vocabulary](vocabulary/united-states-steel-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 2 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [U.S. Steel Spectral Rules](rules/united-states-steel-spectral-rules.yml) — 25 rules across 10 categories enforcing U.S. Steel API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
