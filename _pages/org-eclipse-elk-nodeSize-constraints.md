---
layout: page
title: Node Size Constraints
type: option
---

**Identifier:** org.eclipse.elk.nodeSize.constraints
**Meta Data Provider:** core.options.CoreOptions
**Type:** java.util.EnumSet&lt;org.eclipse.elk.core.options.SizeConstraint&gt;
**Default Value:**  EnumSet.noneOf(SizeConstraint)  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** nodes

### Description
Constraints for determining node sizes. Each member of the set specifies something that should be taken into account when calculating node sizes. The empty set corresponds to node sizes being fixed.

**Containing Groups:** [nodeSize](org-eclipse-elk-nodeSize)

