---
layout: page
title: Neato
type: algorithm
---
org.eclipse.elk.graphviz.neato

Spring model layouts. Neato attempts to minimize a global energy function, which is equivalent to statistical multi-dimensional scaling. The solution is achieved using stress majorization, though the older Kamada-Kawai algorithm, using steepest descent, is also available.

## Preview
![](images/neato.png)

## Meta Data Provider
layouter.GraphvizMetaDataProvider

## Supported Graph Features
SELF_LOOPS
MULTI_EDGES
EDGE_LABELS

## Category
### Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Node Spacing](org-eclipse-elk-spacing-node) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@643fe6d1 (value: 20) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@3e90703 (value: 40)
[Border Spacing](org-eclipse-elk-spacing-border) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@44a24c7d (value: 12) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@6b5323ca (value: 10)
[Label Spacing](org-eclipse-elk-spacing-label) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@62be5539 (value: 0) | 
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | <XFeatureCallImplCustom>.noneOf(<XFeatureCallImplCustom>) | 
[Node Size Options](org-eclipse-elk-nodeSize-options) | <XFeatureCallImplCustom>.of(<XMemberFeatureCallImplCustom>,<XMemberFeatureCallImplCustom>) | 
[Randomization Seed](org-eclipse-elk-randomSeed) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@3c2a40f9 (value: 1)
[Interactive](org-eclipse-elk-interactive) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@1521606c (isTrue: false) | 
[Edge Routing](org-eclipse-elk-edgeRouting) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.SPLINES
[Debug Mode](org-eclipse-elk-debugMode) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@37404760 (isTrue: false) | 
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) |  | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3392829 (isTrue: false)
[Concentrate Edges](org-eclipse-elk-graphviz-concentrate) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3b03098a (isTrue: false) | 
[Epsilon](org-eclipse-elk-graphviz-epsilon) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@3fdfefab (value: 0.0001f)
[Label Distance](org-eclipse-elk-graphviz-labelDistance) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@7b999246 (value: 1) | 
[Label Angle](org-eclipse-elk-graphviz-labelAngle) | - <XNumberLiteralImpl> | 
[Max. Iterations](org-eclipse-elk-graphviz-maxiter) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@7d451dc1 (value: 200)
[Distance Model](org-eclipse-elk-graphviz-neatoModel) | <XFeatureCallImplCustom>.SHORTPATH | 
[Overlap Removal](org-eclipse-elk-graphviz-overlapMode) | <XFeatureCallImplCustom>.PRISM | 
[Adapt Port Positions](org-eclipse-elk-graphviz-adaptPortPositions) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@7a548cd6 (isTrue: true) | 

