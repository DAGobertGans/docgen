---
layout: page
title: Cycle Breaking Strategy
type: option
---
## Cycle Breaking Strategy

----|----
**Identifier:** | org.eclipse.elk.layered.cycleBreaking.strategy
**Meta Data Provider:** | properties.LayeredMetaDataProvider
**Value Type:** | `org.eclipse.elk.alg.layered.p1cycles.CycleBreakingStrategy` (Enum)
**Possible Values:** | `GREEDY`, `INTERACTIVE`
**Default Value:** | `CycleBreakingStrategy.GREEDY` (as defined in org.eclipse.elk.layered)
**Applies To:** | parents
**Legacy Id:** | de.cau.cs.kieler.klay.layered.cycleBreaking
**Containing Groups:** | [cycleBreaking](org-eclipse-elk-layered-cycleBreaking)


### Description
Strategy for cycle breaking. Cycle breaking looks for cycles in the graph and determines which edges to reverse to break the cycles. Reversed edges will end up pointing to the opposite direction of regular edges (that is, reversed edges will point left if edges usually point right).

