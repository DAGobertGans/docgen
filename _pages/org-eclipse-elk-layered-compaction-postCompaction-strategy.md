---
layout: page
title: Post Compaction Strategy
type: option
---
## Post Compaction Strategy

----|----
**Type:** | advanced
**Identifier:** | org.eclipse.elk.layered.compaction.postCompaction.strategy
**Meta Data Provider:** | properties.LayeredMetaDataProvider
**Value Type:** | `org.eclipse.elk.alg.layered.intermediate.compaction.GraphCompactionStrategy` (Enum)
**Possible Values:** | `EDGE_LENGTH`, `LEFT`, `LEFT_RIGHT_CONNECTION_LOCKING`, `LEFT_RIGHT_CONSTRAINT_LOCKING`, `NONE`, `RIGHT`
**Default Value:** | `GraphCompactionStrategy.NONE` (as defined in org.eclipse.elk.layered)
**Applies To:** | parents
**Legacy Id:** | de.cau.cs.kieler.klay.layered.postCompaction
**Containing Groups:** | [compaction](org-eclipse-elk-layered-compaction) -> [postCompaction](org-eclipse-elk-layered-compaction-postCompaction)


### Description
Specifies whether and how post-process compaction is applied.

