\# transform and apply — Synthetic telecom subscribers

Goal: compare each subscriber with their region — share of regional revenue, rank inside the region, deviation from the regional mean/median.

Method: `groupby().transform()`, `groupby().rank()`, `groupby().apply()`.

Result: top-3 subscribers per region found with `apply` and with `sort\_values` + `head` (same 12 rows); mean revenue is above the median in every region.

Key takeaway: `transform` keeps the table size and adds group context to each row; prefer built-in methods over `apply`; use the median as a baseline for skewed revenue.



AI assistance

