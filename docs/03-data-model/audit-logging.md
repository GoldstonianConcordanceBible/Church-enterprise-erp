# docs/03-data-model/audit-logging.md

# Audit Logging

## Purpose

Every major action inside the ERP should create an audit trail for accountability, security, compliance, and trust.

## Audit Events

Track:

- User login
- Permission changes
- Financial record changes
- Donation edits
- Payroll changes
- Vendor changes
- Purchase approvals
- Child check-in/check-out
- Pastoral care access
- Governance votes
- Policy approvals
- Deleted records
- Exported reports

## Audit Fields

Each audit log should include:

- Tenant ID
- User ID
- Action
- Module
- Record type
- Record ID
- Previous value
- New value
- Timestamp
- IP address
- Device/session ID

## Rule

No sensitive record should be edited or deleted without a traceable audit entry.