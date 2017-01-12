---
layout: page
title: Merge Edges
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.mergeEdges
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** boolean
**Default Value:**  false  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Edges that have no ports are merged so they touch the connected nodes at the same points. When this option is disabled, one port is created for each edge directly connected to a node. When it is enabled, all such incoming edges share an input port, and all outgoing edges share an output port.

**Legacy Id:** de.cau.cs.kieler.klay.layered.mergeEdges

