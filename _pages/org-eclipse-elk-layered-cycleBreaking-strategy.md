---
layout: page
title: Cycle Breaking Strategy
type: option
---

**Identifier:** org.eclipse.elk.layered.cycleBreaking.strategy
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** org.eclipse.elk.alg.layered.p1cycles.CycleBreakingStrategy
**Default Value:**  CycleBreakingStrategy.GREEDY  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Strategy for cycle breaking. Cycle breaking looks for cycles in the graph and determines which edges to reverse to break the cycles. Reversed edges will end up pointing to the opposite direction of regular edges (that is, reversed edges will point left if edges usually point right).

**Legacy Id:** de.cau.cs.kieler.klay.layered.cycleBreaking
**Containing Groups:** [cycleBreaking](org-eclipse-elk-layered-cycleBreaking)

