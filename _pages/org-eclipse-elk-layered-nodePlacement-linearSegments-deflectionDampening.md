---
layout: page
title: Linear Segments Deflection Dampening
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.nodePlacement.linearSegments.deflectionDampening
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** double
**Default Value:**  0.3  (not specific to an algorithm)
**Lower Bound:**  ExclusiveBounds.greaterThan(0)
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Dampens the movement of nodes to keep the diagram from getting too large.

**Legacy Id:** de.cau.cs.kieler.klay.layered.linearSegmentsDeflectionDampening
**Dependencies:** org.eclipse.elk.layered.nodePlacement.strategy
**Containing Groups:** [nodePlacement](org-eclipse-elk-layered-nodePlacement) -> [linearSegments](org-eclipse-elk-layered-nodePlacement-linearSegments)

