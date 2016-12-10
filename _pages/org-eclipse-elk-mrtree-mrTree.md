---
layout: page
title: ELK Mr. Tree
type: algorithm
---
org.eclipse.elk.mrtree.mrTree

Tree-based algorithm provided by the Eclipse Layout Kernel. Computes a spanning tree of         the input graph and arranges all nodes according to the resulting parent-children         hierarchy. I pity the fool who doesn't use Mr. Tree Layout.

## Preview
![](images/tree.png)

## Meta Data Provider
properties.MrTreeMetaDataProvider

## Supported Graph Features
DISCONNECTED

## Category
### Tree
Specialized layout methods for trees, i.e. acyclic graphs. The regular structure of graphs that have no undirected cycles can be emphasized using an algorithm of this type.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Node Spacing](org-eclipse-elk-spacing-node) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1119eba8 (value: 20) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1f368496 (value: 20)
[Border Spacing](org-eclipse-elk-spacing-border) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@4a00f35f (value: 12) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@5a8d8062 (value: 20)
[Aspect Ratio](org-eclipse-elk-aspectRatio) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@3f48e287 (value: 1.6f)
[Priority](org-eclipse-elk-priority) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@157f2b2 (value: 1)
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) |  | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@632d3d91 (isTrue: true)
[Direction](org-eclipse-elk-direction) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.DOWN
[Debug Mode](org-eclipse-elk-debugMode) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@691be50d (isTrue: false) | 
[Weighting of Nodes](org-eclipse-elk-mrtree-weighting) | <XFeatureCallImplCustom>.DESCENDANTS | 
[Search Order](org-eclipse-elk-mrtree-searchOrder) | <XFeatureCallImplCustom>.DFS | 

