---
layout: page
title: No Layout
type: option
---
programmatic

**Identifier:** org.eclipse.elk.noLayout
**Meta Data Provider:** core.options.CoreOptions
**Type:** boolean
**Default Value:**  false  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** nodes, edges, ports, labels

### Description
No layout is done for the associated element. This is used to mark parts of a diagram to avoid their inclusion in the layout graph, or to mark parts of the layout graph to prevent layout engines from processing them. If you wish to exclude the contents of a compound node from automatic layout, while the node itself is still considered on its own layer, use the 'Fixed Layout' algorithm for that node.

**Legacy Id:** de.cau.cs.kieler.noLayout

