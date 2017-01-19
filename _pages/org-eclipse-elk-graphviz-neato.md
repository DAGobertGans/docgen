---
layout: page
title: Neato
type: algorithm
---
## Neato
![](images/neato.png)
**Identifier:** org.eclipse.elk.graphviz.neato
**Meta Data Provider:** layouter.GraphvizMetaDataProvider

Spring model layouts. Neato attempts to minimize a global energy function, which is equivalent to statistical multi-dimensional scaling. The solution is achieved using stress majorization, though the older Kamada-Kawai algorithm, using steepest descent, is also available.

## Category: Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

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
[Distance Model](org-eclipse-elk-graphviz-neatoModel) | `NeatoModel` | `NeatoModel.SHORTPATH` | org.eclipse.elk.graphviz.neatoModel
[Edge Label Spacing](org-eclipse-elk-spacing-edgeLabel) | `double` | `5` | org.eclipse.elk.spacing.edgeLabel
[Edge Routing](org-eclipse-elk-edgeRouting) | `EdgeRouting` | `EdgeRouting.SPLINES` | org.eclipse.elk.edgeRouting
[Epsilon](org-eclipse-elk-graphviz-epsilon) | `double` | `0.0001f` | org.eclipse.elk.graphviz.epsilon
[Interactive](org-eclipse-elk-interactive) | `boolean` | `false` | org.eclipse.elk.interactive
[Label Angle](org-eclipse-elk-graphviz-labelAngle) | `double` | `-25` | org.eclipse.elk.graphviz.labelAngle
[Label Distance](org-eclipse-elk-graphviz-labelDistance) | `double` | `1` | org.eclipse.elk.graphviz.labelDistance
[Max. Iterations](org-eclipse-elk-graphviz-maxiter) | `int` | `200` | org.eclipse.elk.graphviz.maxiter
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | `EnumSet<SizeConstraint>` | `EnumSet.noneOf(SizeConstraint)` | org.eclipse.elk.nodeSize.constraints
[Node Size Options](org-eclipse-elk-nodeSize-options) | `EnumSet<SizeOptions>` | `EnumSet.of(SizeOptions.DEFAULT_MINIMUM_SIZE, SizeOptions.APPLY_ADDITIONAL_PADDING)` | org.eclipse.elk.nodeSize.options
[Node Spacing](org-eclipse-elk-spacing-nodeNode) | `double` | `40` | org.eclipse.elk.spacing.nodeNode
[Overlap Removal](org-eclipse-elk-graphviz-overlapMode) | `OverlapMode` | `OverlapMode.PRISM` | org.eclipse.elk.graphviz.overlapMode
[Padding](org-eclipse-elk-padding) | `ElkPadding` | `new ElkPadding(10)` | org.eclipse.elk.padding
[Randomization Seed](org-eclipse-elk-randomSeed) | `int` | `1` | org.eclipse.elk.randomSeed
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) | `boolean` | `false` | org.eclipse.elk.separateConnectedComponents

