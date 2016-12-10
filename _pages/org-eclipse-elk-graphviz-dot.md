---
layout: page
title: Dot
type: algorithm
---
org.eclipse.elk.graphviz.dot

Layered drawings of directed graphs. The algorithm aims edges in the same direction (top to bottom, or left to right) and then attempts to avoid edge crossings and reduce edge length. Edges are routed as spline curves and are thus drawn very smoothly. This algorithm is very suitable for state machine and activity diagrams, where the direction of edges has an important role.

## Preview
![](images/dot.png)

## Meta Data Provider
layouter.GraphvizMetaDataProvider

## Supported Graph Features
SELF_LOOPS
MULTI_EDGES
EDGE_LABELS
COMPOUND
CLUSTERS

## Category
### Layered
The layer-based method was introduced by Sugiyama, Tagawa and Toda in 1981. It emphasizes the direction of edges by pointing as many edges as possible into the same direction. The nodes are arranged in layers, which are sometimes called "hierarchies", and then reordered such that the number of edge crossings is minimized. Afterwards, concrete coordinates are computed for the nodes and edge bend points.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Direction](org-eclipse-elk-direction) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.DOWN
[Node Spacing](org-eclipse-elk-spacing-node) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@643fe6d1 (value: 20) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@2e8333c (value: 20)
[Border Spacing](org-eclipse-elk-spacing-border) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@44a24c7d (value: 12) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@2ada12dd (value: 10)
[Label Spacing](org-eclipse-elk-spacing-label) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@62be5539 (value: 0) | 
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | <XFeatureCallImplCustom>.noneOf(<XFeatureCallImplCustom>) | 
[Node Size Options](org-eclipse-elk-nodeSize-options) | <XFeatureCallImplCustom>.of(<XMemberFeatureCallImplCustom>,<XMemberFeatureCallImplCustom>) | 
[Edge Routing](org-eclipse-elk-edgeRouting) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.SPLINES
[Debug Mode](org-eclipse-elk-debugMode) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@37404760 (isTrue: false) | 
[Hierarchy Handling](org-eclipse-elk-hierarchyHandling) | <XFeatureCallImplCustom>.INHERIT | 
[Iterations Factor](org-eclipse-elk-graphviz-iterationsFactor) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@737db193 (value: 1)
[Concentrate Edges](org-eclipse-elk-graphviz-concentrate) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3b03098a (isTrue: false) | 
[Label Distance](org-eclipse-elk-graphviz-labelDistance) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@7b999246 (value: 1) | 
[Label Angle](org-eclipse-elk-graphviz-labelAngle) | - <XNumberLiteralImpl> | 
[Layer Spacing Factor](org-eclipse-elk-graphviz-layerSpacingFactor) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@25e712e5 (value: 1) | 
[Adapt Port Positions](org-eclipse-elk-graphviz-adaptPortPositions) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@7a548cd6 (isTrue: true) | 

