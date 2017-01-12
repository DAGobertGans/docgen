---
layout: page
title: Scale Factor
type: option
---
programmatic

**Identifier:** org.eclipse.elk.scaleFactor
**Meta Data Provider:** core.options.CoreOptions
**Type:** double
**Default Value:**  1  (not specific to an algorithm)
**Lower Bound:**  ExclusiveBounds.greaterThan(0)
**Upper Bound:** *not defined*
**Applies To:** nodes

### Description
The scaling factor to be applied to the corresponding node in recursive layout. It causes the corresponding node's size to be adjusted, and its ports and labels to be sized and placed accordingly after the layout of that node has been determined (and before the node itself and its siblings are arranged). The scaling is not reverted afterwards, so the resulting layout graph contains the adjusted size and position data. This option is currently not supported if 'Layout Hierarchy' is set.

**Legacy Id:** de.cau.cs.kieler.scaleFactor
**Dependencies:** org.eclipse.elk.layoutHierarchy

