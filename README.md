# TAQ NBBO TimescaleDB Implementation

## Overview
High-performance financial market data pipeline processing 440M+ daily NBBO records with nanosecond precision.

## Quick Start
1. Clone this repository
2. Execute `taq_nbbo_timescaledb.sql` in your TimescaleDB instance
3. Follow the workflow instructions in the SQL file

## Files
- `taq_nbbo_timescaledb.sql` - Complete database setup and functions
- `sample_queries.sql` - Example analytical queries
- `docs/` - Additional documentation

## Performance
- Processes 440M records in 57 minutes
- Sub-second query times for most analysis patterns
- Maintains full nanosecond precision
