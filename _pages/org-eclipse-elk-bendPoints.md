---
layout: page
title: Bend Points
type: option
---
programmatic

**Identifier:** org.eclipse.elk.bendPoints
**Meta Data Provider:** core.options.CoreOptions
**Type:** org.eclipse.elk.core.math.KVectorChain
**Default Value:** *not defined*  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** edges

### Description
A fixed list of bend points for the edge. This is used by the 'Fixed Layout' algorithm to specify a pre-defined routing for an edge. The vector chain must include the source point, any bend points, and the target point, so it must have at least two points.

**Legacy Id:** de.cau.cs.kieler.bendPoints

