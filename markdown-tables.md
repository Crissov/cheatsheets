# Pipe table

## Canonical pipe table

| th |
| -- |
| td |

## Verbose pipe table

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

# Minimal 2×2 tables

## Minimal pipe table

th | th
-- | --
td | td

## Minimal grid table

th | th
---+---
td | td

## Minimal ‘row’ table

th | th
-------
td | td

## Minimal ‘fusion’ table

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

## Corner table with two rows

,----.
| th |
+----+
| td |
`----'

## Corner table with two columns

,----+----.
| td | td |
`----+----'

# MediaWiki-inspired tables

## Original

{| .class #id attribute=value
 | td || td
 |}

## Explicit row breaks

! th ! th !
|---------- tr
| td | td |

## Implicit row breaks, explicit caption

|+ caption
! th !! th
| td || td

## Fenced

||| .class #id
|+ caption
|--------------
! th !! th !!attribute=value| th
! th
|-
| td || td ||attribute=value| td
| td
|||

# Horizontal alignment

## Pipe table
using colon attractors

| th | th[align=left] | th[align=center] | th[align=right] |
| -- |:-------------- |:----------------:| ---------------:|
| td | td[align=left] | td[align=center] | td[align=right] |

## Grid table
using space repulsors

| th |th[align=left] |th[align=center]| th[align=right]|
+----+---------------+----------------+----------------+
| td |td[align=left] |td[align=center]| td[align=right]|

## Simple table
using space repulsors

th th[align=left]     th[align=center]     th[align=right]
-- ---------------- -------------------- -----------------
td td[align=left]     td[align=center]     td[align=right]

# Cell spans

## Pipe table
using multiple adjacent pipes

| th[colspan=2] ||
| ----- | ------ |
| td    |   td   |

## Simple table
crossing gaps

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

## Double-dash caption

| td | td |
-- caption

## MediaWiki caption

|+ caption
| td | td |
