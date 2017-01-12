---
layout: page
title: Add Unnecessary Bendpoints
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.unnecessaryBendpoints
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** boolean
**Default Value:**  false  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Adds bend points even if an edge does not change direction. If true, each long edge dummy will contribute a bend point to its edges and hierarchy-crossing edges will always get a bend point where they cross hierarchy boundaries. By default, bend points are only added where an edge changes direction.

**Legacy Id:** de.cau.cs.kieler.klay.layered.unnecessaryBendpoints

