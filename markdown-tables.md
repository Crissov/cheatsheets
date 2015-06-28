# Pipe table

| th |
| -- |
| td |

| th |
|----|
| td |

# Simple table

## Simple table with head

 th   th
---- ----
 td   td

## Simple table without head

---- ----
 td   td
---------

## Verbose simple table with head

---------
 th   th
---- ----
 td   td
---------

# Minimal tables

## Minimal pipe table

th | th
-- | --
td | td

## Minimal grid table

th | th
---+---
td | td

## Minimal **???** table

th | th
-------
td | td

## Minimal **???** table

th | th
--- ---
td | td

## Minimal simple table

 th   th
---- ----
 td   td

# Grid table

+----+----+
| th | td |
+====+----+
| td | td |
+----+----+

# Corner table

,----.
| th |
+----+
| td |
`----'

# Horizontal alignment

## Pipe table

| th | th[align=left] | th[align=center] | th[align=right] |
| -- |:-------------- |:----------------:| ---------------:|
| td | td[align=left] | td[align=center] | td[align=right] |

## 

| th |th[align=left] |th[align=center]| th[align=right]|
+----+---------------+----------------+----------------+
| td |td[align=left] |td[align=center]| td[align=right]|

## Simple table

th th[align=left]     th[align=center]     th[align=right]
-- ---------------- -------------------- -----------------
td td[align=left]     td[align=center]     td[align=right]

# Cell spans

## Pipe table

| th[colspan=2] ||
| ----- | ------ |
| td    |   td   |

## Simple table

 th[colspan=2]
------- -------
   td     td

# Caption

## Bottom colon caption

| td | td |
: caption

## Top colon caption

: caption
| td | td |

## Bottom colon caption with label

| td | td |
Table: caption

## Top colon caption with label

Table: caption
| td | td |

## Bottom bracket caption

| td | td |
[caption]

## Top bracket caption

[caption]
| td | td |

