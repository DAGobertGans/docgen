---
layout: page
title: Edge Routing
type: option
---

**Identifier:** org.eclipse.elk.edgeRouting
**Meta Data Provider:** core.options.CoreOptions
**Type:** org.eclipse.elk.core.options.EdgeRouting
**Default Value:**  EdgeRouting.UNDEFINED  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
What kind of edge routing style should be applied for the content of a parent node. Algorithms may also set this option to single edges in order to mark them as splines. The bend point list of edges with this option set to SPLINES must be interpreted as control points for a piecewise cubic spline.

**Legacy Id:** de.cau.cs.kieler.edgeRouting

