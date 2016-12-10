---
layout: page
title: FDP
type: algorithm
---
org.eclipse.elk.graphviz.fdp

Spring model layouts similar to those of Neato, but does this by reducing forces rather than working with energy. Fdp implements the Fruchterman-Reingold heuristic including a multigrid solver that handles larger graphs and clustered undirected graphs.

## Preview
![](images/fdp.png)

## Meta Data Provider
layouter.GraphvizMetaDataProvider

## Supported Graph Features
SELF_LOOPS
MULTI_EDGES
EDGE_LABELS
CLUSTERS

## Category
### Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Node Spacing](org-eclipse-elk-spacing-node) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@643fe6d1 (value: 20) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@3d7b1744 (value: 40)
[Border Spacing](org-eclipse-elk-spacing-border) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@44a24c7d (value: 12) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1d07b7f0 (value: 10)
[Label Spacing](org-eclipse-elk-spacing-label) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@62be5539 (value: 0) | 
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | <XFeatureCallImplCustom>.noneOf(<XFeatureCallImplCustom>) | 
[Node Size Options](org-eclipse-elk-nodeSize-options) | <XFeatureCallImplCustom>.of(<XMemberFeatureCallImplCustom>,<XMemberFeatureCallImplCustom>) | 
[Interactive](org-eclipse-elk-interactive) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@1521606c (isTrue: false) | 
[Edge Routing](org-eclipse-elk-edgeRouting) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.SPLINES
[Debug Mode](org-eclipse-elk-debugMode) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@37404760 (isTrue: false) | 
[Hierarchy Handling](org-eclipse-elk-hierarchyHandling) | <XFeatureCallImplCustom>.INHERIT | 
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) |  | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@64c2d7fd (isTrue: false)
[Concentrate Edges](org-eclipse-elk-graphviz-concentrate) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3b03098a (isTrue: false) | 
[Label Distance](org-eclipse-elk-graphviz-labelDistance) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@7b999246 (value: 1) | 
[Label Angle](org-eclipse-elk-graphviz-labelAngle) | - <XNumberLiteralImpl> | 
[Max. Iterations](org-eclipse-elk-graphviz-maxiter) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@43916f78 (value: 600)
[Overlap Removal](org-eclipse-elk-graphviz-overlapMode) | <XFeatureCallImplCustom>.PRISM | 
[Adapt Port Positions](org-eclipse-elk-graphviz-adaptPortPositions) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@7a548cd6 (isTrue: true) | 

