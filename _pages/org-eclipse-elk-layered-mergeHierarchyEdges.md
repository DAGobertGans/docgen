---
layout: page
title: Merge Hierarchy-Crossing Edges
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.mergeHierarchyEdges
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** boolean
**Default Value:**  true  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
If hierarchical layout is active, hierarchy-crossing edges use as few hierarchical ports as possible. They are broken by the algorithm, with hierarchical ports inserted as required. Usually, one such port is created for each edge at each hierarchy crossing point. With this option set to true, we try to create as few hierarchical ports as possible in the process. In particular, all edges that form a hyperedge can share a port.

**Legacy Id:** de.cau.cs.kieler.klay.layered.mergeHierarchyEdges

