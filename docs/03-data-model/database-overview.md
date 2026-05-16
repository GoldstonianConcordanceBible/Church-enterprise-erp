# docs/03-data-model/database-overview.md

# Database Overview

## Purpose

The Church Enterprise ERP uses a multi-tenant database model to support churches, ministries, schools, daycare centers, nonprofits, campuses, and related entities inside one platform.

## Core Design Principles

- Every organization is a tenant
- Every tenant can have multiple campuses
- Every campus can have ministries, departments, events, facilities, staff, members, and financial records
- Every module must connect back to people, money, ministry, and mission
- Every sensitive action must create an audit trail

## Suggested Database Stack

- PostgreSQL for primary relational data
- Redis for queues and caching
- S3-compatible storage for documents and media
- Vector database for AI search and semantic retrieval
- Data warehouse layer for analytics