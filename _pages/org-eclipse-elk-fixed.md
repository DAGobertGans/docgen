---
layout: page
title: Fixed Layout
type: algorithm
---
## Fixed Layout
**Identifier:** org.eclipse.elk.fixed
**Meta Data Provider:** core.options.CoreOptions

Keeps the current layout as it is, without any automatic modification. Optional coordinates can be given for nodes and edge bend points.

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Bend Points](org-eclipse-elk-bendPoints) | `KVectorChain` | `*not defined*` | org.eclipse.elk.bendPoints
[Minimum Height](org-eclipse-elk-nodeSize-minHeight) | `double` | `0` | org.eclipse.elk.nodeSize.minHeight
[Minimum Width](org-eclipse-elk-nodeSize-minWidth) | `double` | `0` | org.eclipse.elk.nodeSize.minWidth
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | `EnumSet<SizeConstraint>` | `EnumSet.noneOf(SizeConstraint)` | org.eclipse.elk.nodeSize.constraints
[Node Size Minimum](org-eclipse-elk-nodeSize-minimum) | `KVector` | `*not defined*` | org.eclipse.elk.nodeSize.minimum
[Padding](org-eclipse-elk-padding) | `ElkPadding` | `new ElkPadding(15)` | org.eclipse.elk.padding
[Position](org-eclipse-elk-position) | `KVector` | `*not defined*` | org.eclipse.elk.position

