---
layout: page
title: Fixed Layout
type: algorithm
---
**Identifier:** org.eclipse.elk.fixed
**Meta Data Provider:** core.options.CoreOptions

Keeps the current layout as it is, without any automatic modification. Optional coordinates can be given for nodes and edge bend points.

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Padding](org-eclipse-elk-padding) | ElkPadding |  new ElkPadding(15) | org.eclipse.elk.padding
[Position](org-eclipse-elk-position) | KVector | *not defined* | org.eclipse.elk.position
[Bend Points](org-eclipse-elk-bendPoints) | KVectorChain | *not defined* | org.eclipse.elk.bendPoints
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | EnumSet&lt;SizeConstraint&gt; | *not defined* | org.eclipse.elk.nodeSize.constraints
[Node Size Minimum](org-eclipse-elk-nodeSize-minimum) | KVector | *not defined* | org.eclipse.elk.nodeSize.minimum
[Minimum Width](org-eclipse-elk-nodeSize-minWidth) | double | *not defined* | org.eclipse.elk.nodeSize.minWidth
[Minimum Height](org-eclipse-elk-nodeSize-minHeight) | double | *not defined* | org.eclipse.elk.nodeSize.minHeight

