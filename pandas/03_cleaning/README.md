\# pandas: data cleaning — synthetic subscribers

Goal: clean a messy subscriber export (duplicates, text numbers, mixed date formats, messy text, missing values).

Model: no model — read\_csv, drop\_duplicates, to\_numeric, to\_datetime, str methods, fillna, groupby transform.

Result: 7 problems fixed; missing fee filled with tariff median (2500) instead of overall median (5250).

Key takeaway: fill estimates within their group, never invent facts like dates.



AI assistance: built with Claude (Anthropic) as a coding co-pilot. I reviewed, ran and commented the code myself.

