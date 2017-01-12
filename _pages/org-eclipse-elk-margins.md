---
layout: page
title: Margins
type: option
---
programmatic

**Identifier:** org.eclipse.elk.margins
**Meta Data Provider:** core.options.CoreOptions
**Type:** org.eclipse.elk.core.math.ElkMargin
**Default Value:**  new ElkMargin()  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** nodes

### Description
Margins define additional space around the actual bounds of a graph element. For instance, ports or labels being placed on the outside of a node's border might introduce such a margin. The margin is used to guarantee non-overlap of other graph elements with those ports or labels.

**Legacy Id:** de.cau.cs.kieler.margins

