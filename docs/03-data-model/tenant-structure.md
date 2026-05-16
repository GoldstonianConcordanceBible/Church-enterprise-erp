# docs/03-data-model/tenant-structure.md

# Tenant Structure

## Primary Tenant Model

Each church or organization is a tenant.

## Tenant Entities

- Organization
- Campus
- Department
- Ministry
- Cost Center
- Legal Entity
- School
- Daycare
- Foundation
- Mission Entity

## Example Structure

Church Organization
→ Main Campus
→ North Campus
→ Online Campus
→ Daycare Center
→ Christian School
→ Missions Foundation
→ Media Ministry

## Multi-Tenant Requirements

- Tenant isolation
- Role-based permissions
- Campus-level access
- Department-level access
- Module-level access
- Audit logs by tenant
- Configurable branding per tenant
- Configurable chart of accounts per tenant