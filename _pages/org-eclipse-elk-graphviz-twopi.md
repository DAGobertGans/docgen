---
layout: page
title: Twopi
type: algorithm
---
## Twopi
![](images/twopi.png)
**Identifier:** org.eclipse.elk.graphviz.twopi
**Meta Data Provider:** layouter.GraphvizMetaDataProvider

Radial layouts, after Wills '97. The nodes are placed on concentric circles depending on their distance from a given root node. The algorithm is designed to handle not only small graphs, but also very large ones.

## Category: Tree
Specialized layout methods for trees, i.e. acyclic graphs. The regular structure of graphs that have no undirected cycles can be emphasized using an algorithm of this type.

## Supported Graph Features

Name | Description
----|----
Self Loops | Edges connecting a node with itself.
Multi Edges | Multiple edges with the same source and target node.
Edge Labels | Labels that are associated with edges.

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Adapt Port Positions](org-eclipse-elk-graphviz-adaptPortPositions) | `boolean` | `true` | org.eclipse.elk.graphviz.adaptPortPositions
[Concentrate Edges](org-eclipse-elk-graphviz-concentrate) | `boolean` | `false` | org.eclipse.elk.graphviz.concentrate
[Debug Mode](org-eclipse-elk-debugMode) | `boolean` | `false` | org.eclipse.elk.debugMode
[Edge Label Spacing](org-eclipse-elk-spacing-edgeLabel) | `double` | `5` | org.eclipse.elk.spacing.edgeLabel
[Edge Routing](org-eclipse-elk-edgeRouting) | `EdgeRouting` | `EdgeRouting.SPLINES` | org.eclipse.elk.edgeRouting
[Label Angle](org-eclipse-elk-graphviz-labelAngle) | `double` | `-25` | org.eclipse.elk.graphviz.labelAngle
[Label Distance](org-eclipse-elk-graphviz-labelDistance) | `double` | `1` | org.eclipse.elk.graphviz.labelDistance
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | `EnumSet<SizeConstraint>` | `EnumSet.noneOf(SizeConstraint)` | org.eclipse.elk.nodeSize.constraints
[Node Size Options](org-eclipse-elk-nodeSize-options) | `EnumSet<SizeOptions>` | `EnumSet.of(SizeOptions.DEFAULT_MINIMUM_SIZE, SizeOptions.APPLY_ADDITIONAL_PADDING)` | org.eclipse.elk.nodeSize.options
[Node Spacing](org-eclipse-elk-spacing-nodeNode) | `double` | `60` | org.eclipse.elk.spacing.nodeNode
[Overlap Removal](org-eclipse-elk-graphviz-overlapMode) | `OverlapMode` | `OverlapMode.PRISM` | org.eclipse.elk.graphviz.overlapMode
[Padding](org-eclipse-elk-padding) | `ElkPadding` | `new ElkPadding(10)` | org.eclipse.elk.padding

