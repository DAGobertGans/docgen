---
layout: page
title: Node Label Placement
type: option
---
## Node Label Placement

----|----
**Identifier:** | org.eclipse.elk.nodeLabels.placement
**Meta Data Provider:** | core.options.CoreOptions
**Value Type:** | `java.util.EnumSet<org.eclipse.elk.core.options.NodeLabelPlacement>`
**Possible Values:** | *`@ExperimentalPropertyValue`* *`@AdvancedPropertyValue`* `H_CENTER`, `H_LEFT`, `H_PRIORITY`, `H_RIGHT`, `INSIDE`, `OUTSIDE`, `V_BOTTOM`, `V_CENTER`, `V_TOP`
**Default Value:** | `NodeLabelPlacement.fixed` (as defined in org.eclipse.elk)
**Applies To:** | nodes, labels
**Legacy Id:** | de.cau.cs.kieler.nodeLabelPlacement
**Containing Groups:** | [nodeLabels](org-eclipse-elk-nodeLabels)


### Description
Hints for where node labels are to be placed; if empty, the node label's position is not modified.

