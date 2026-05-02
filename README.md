# Oracle General Ledger (oracle-general-ledger)

Oracle Fusion Cloud General Ledger provides REST APIs for managing core financial accounting operations within Oracle Cloud ERP. These APIs enable programmatic access to journal entries, ledger balances, accounting periods, currency rates, intercompany transactions, budgetary controls, and chart of accounts configurations used by finance teams for enterprise accounting, reporting, and close processes.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-general-ledger/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Accounting
- Balances
- Cloud
- ERP
- Finance
- General Ledger
- Journals

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-03-16

## APIs

### Oracle General Ledger Journal Batches REST API

REST API for managing journal batches in Oracle Fusion Cloud General Ledger. The journal batches resource allows viewing journal batches, updating batch completion status and reversal attributes, and deleting journal batches. Child resources provide access to journal headers, journal lines, attachments, action logs, descriptive flexfields, and error details.

**Human URL:** https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html

**Base URL:** https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05

### Oracle General Ledger Ledger Balances REST API

REST API for querying account balances in Oracle Fusion Cloud General Ledger. The ledger balances resource allows viewing balance amounts for any account combination or accounts defined as part of an account group. Supports finders for account balance by combination, account group balance, and primary key lookup across ledgers, currencies, and accounting periods.

### Oracle General Ledger Accounting Period Status REST API

REST API for viewing accounting period statuses in Oracle Fusion Cloud General Ledger. The accounting period status list of values resource provides period details in a calendar, including ledger identification, period name, and closing status values such as Open, Closed, Future Enterable, Never Opened, Permanently Closed, and Close Pending.

### Oracle General Ledger Currency Rates REST API

REST API for retrieving currency exchange rate information in Oracle Fusion Cloud General Ledger. The currency rates resource provides information on currency rates for source and target currency combinations, supporting daily rates, corporate rates, and user-defined rate types used in multi-currency accounting and foreign currency translation.

### Oracle General Ledger Ledger Options REST API

REST API for accessing ledger configuration options in Oracle Fusion Cloud General Ledger. The ledger options resource provides access to ledger setup details including chart of accounts identifiers, balancing segment names, accounted period types, budgetary control settings, and document numbering configurations used to define how a ledger processes accounting data.

### Oracle General Ledger Budgetary Control REST API

REST API for managing budgetary controls in Oracle Fusion Cloud General Ledger. The budgetary control resources enable viewing budget execution controls, budget impact results, and control budget periods. These APIs support organizations that use budget accounts to control expenditures against defined appropriation limits and enterprise performance management budget transactions.

### Oracle General Ledger Chart of Accounts Filters REST API

REST API for managing chart of accounts filter configurations in Oracle Fusion Cloud General Ledger. The chart of accounts filters resource returns filter ID values for chart of accounts filter criteria, enabling control over which account combinations are available for journal entry and financial reporting based on defined filter rules and criteria.

### Oracle Intercompany Transactions REST API

REST API for managing intercompany transactions in Oracle Fusion Cloud Financials. The intercompany resources support agreement-based intercompany transactions, intercompany transaction source documents, intercompany agreements with transfer authorization groups, and intercompany organization lookups. These APIs enable automated cross-charge processing and intercompany balancing within the general ledger.

### Oracle Joint Venture General Ledger Transactions REST API

REST API for managing joint venture general ledger transactions in Oracle Fusion Cloud Financials. The joint venture GL transactions and joint venture subledger transactions resources enable viewing and updating transactions related to joint venture accounting, supporting partnership accounting workflows that integrate with the general ledger.

### Oracle General Ledger ERP Integrations REST API

REST API for automating bulk data import and export flows with Oracle Fusion Cloud General Ledger. The ERP integrations resource supports loading journal data files, submitting Enterprise Scheduler Service jobs for journal import, and running the accounting engine for subledger journal processing. Also provides access to ERP business events and ERP process status details.

## Common Properties

- [Portal](https://docs.oracle.com/en/cloud/saas/financials/26a/api.html)
- [Documentation](https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html)
- [Authentication](https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html)
- [Change Log](https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html)
- [Implementation Guide](https://docs.oracle.com/en/cloud/saas/financials/26a/faigl/index.html)
- [User Guide](https://docs.oracle.com/en/cloud/saas/financials/26a/faugl/index.html)
- [Support](https://support.oracle.com)
- [Status](https://ocistatus.oraclecloud.com/)
- [Website](https://www.oracle.com/erp/general-ledger/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
