---
layout: page
title: Junction Points
type: option
---
output

**Identifier:** org.eclipse.elk.junctionPoints
**Meta Data Provider:** core.options.CoreOptions
**Type:** org.eclipse.elk.core.math.KVectorChain
**Default Value:**  new KVectorChain()  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** edges

### Description
This option is not used as option, but as output of the layout algorithms. It is attached to edges and determines the points where junction symbols should be drawn in order to represent hyperedges with orthogonal routing. Whether such points are computed depends on the chosen layout algorithm and edge routing style. The points are put into the vector chain with no specific order.

**Legacy Id:** de.cau.cs.kieler.junctionPoints

