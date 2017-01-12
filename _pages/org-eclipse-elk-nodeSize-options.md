---
layout: page
title: Node Size Options
type: option
---

**Identifier:** org.eclipse.elk.nodeSize.options
**Meta Data Provider:** core.options.CoreOptions
**Type:** java.util.EnumSet&lt;org.eclipse.elk.core.options.SizeOptions&gt;
**Default Value:**  EnumSet.of(SizeOptions.DEFAULT_MINIMUM_SIZE, SizeOptions.APPLY_ADDITIONAL_PADDING)  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** nodes

### Description
Options modifying the behavior of the size constraints set on a node. Each member of the set specifies something that should be taken into account when calculating node sizes. The empty set corresponds to no further modifications.

**Containing Groups:** [nodeSize](org-eclipse-elk-nodeSize)

