---
layout: page
title: Favor Straight Edges Over Balancing
type: option
---

**Identifier:** org.eclipse.elk.layered.nodePlacement.favorStraightEdges
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** boolean
**Default Value:** *not defined*  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Favor straight edges over a balanced node placement. The default behavior is determined automatically based on the used 'edgeRouting'. For an orthogonal style it is set to true, for all other styles to false.

**Dependencies:** org.eclipse.elk.layered.nodePlacement.strategy
**Containing Groups:** [nodePlacement](org-eclipse-elk-layered-nodePlacement)

