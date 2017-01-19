---
layout: page
title: Circo
type: algorithm
---
## Circo
![](images/circo.png)
**Identifier:** org.eclipse.elk.graphviz.circo
**Meta Data Provider:** layouter.GraphvizMetaDataProvider

Circular layout, after Six and Tollis '99, Kaufmann and Wiese '02. The algorithm finds biconnected components and arranges each component in a circle, trying to minimize the number of crossings inside the circle. This is suitable for certain diagrams of multiple cyclic structures such as certain telecommunications networks.

## Category: Circle
Circular layout algorithms emphasize cycles or biconnected components of a graph by arranging them in circles. This is useful if a drawing is desired where such components are clearly grouped, or where cycles are shown as prominent OPTIONS of the graph.

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
[Node Spacing](org-eclipse-elk-spacing-nodeNode) | `double` | `40` | org.eclipse.elk.spacing.nodeNode
[Overlap Removal](org-eclipse-elk-graphviz-overlapMode) | `OverlapMode` | `OverlapMode.PRISM` | org.eclipse.elk.graphviz.overlapMode
[Padding](org-eclipse-elk-padding) | `ElkPadding` | `new ElkPadding(10)` | org.eclipse.elk.padding
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) | `boolean` | `false` | org.eclipse.elk.separateConnectedComponents

