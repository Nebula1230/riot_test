# RIOT Analytics - Data Modeling Documentation

##  Modeling Conception

The complete **data architecture design and modeling strategy** is documented in a Jupyter notebook:

** [`riot_test.ipynb`](riot_test.ipynb)**

### Contents

- Architecture strategy
- Storage and retention policies
- Incremental and SCD2 strategies
- Macros and testing approach
- SQL implementation for some use cases
- Testing implementation
---

##  Source Data

**SQLite Database:** [`data/riot_source.db`](data/riot_analytics.db.db)

Contains the source tables:
- `stripe_customers` - Customer profiles and metadata
- `stripe_subscriptions` - Subscription details, status, and MRR

This database serves as the source system for the sql task.

---
