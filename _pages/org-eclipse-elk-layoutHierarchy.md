---
layout: page
title: Layout Hierarchy
type: option
---
deprecated

**Identifier:** org.eclipse.elk.layoutHierarchy
**Meta Data Provider:** core.options.CoreOptions
**Type:** boolean
**Default Value:**  false  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Whether the whole hierarchy shall be layouted. If this option is not set, each hierarchy level of the graph is processed independently, possibly by different layout algorithms, beginning with the lowest level. If it is set, the algorithm is responsible to process all hierarchy levels that are contained in the associated parent node.

**Legacy Id:** de.cau.cs.kieler.layoutHierarchy

