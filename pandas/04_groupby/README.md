\# pandas: groupby \& agg — synthetic telecom payments

Goal: summarize payments by tariff, region and month: revenue, ARPU, unique subscribers.

Model: no model — groupby, agg with named aggregates, nunique, size, value\_counts, reset\_index.

Result: monthly unique subscribers sum to 579, true unique for the period is 284.

Key takeaway: nunique is unique only within a group — never sum it across groups.



AI assistance

