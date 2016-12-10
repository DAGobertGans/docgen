---
layout: page
title: ELK Force
type: algorithm
---
org.eclipse.elk.force

Force-based algorithm provided by the Eclipse Layout Kernel. Implements methods that         follow physical analogies by simulating forces that move the nodes into a balanced         distribution. Currently the original Eades model and the Fruchterman - Reingold model are         supported.

## Preview
![](images/force.png)

## Meta Data Provider
properties.ForceMetaDataProvider

## Supported Graph Features
MULTI_EDGES
EDGE_LABELS

## Category
### Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Priority](org-eclipse-elk-priority) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@11f2b287 (value: 1)
[Node Spacing](org-eclipse-elk-spacing-node) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@5e244a36 (value: 20) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@56d736db (value: 80)
[Border Spacing](org-eclipse-elk-spacing-border) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@6527f9e (value: 12) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1ad03876 (value: 50)
[Label Spacing](org-eclipse-elk-spacing-label) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@209a98fa (value: 0) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@6bcfa80e (value: 5)
[Aspect Ratio](org-eclipse-elk-aspectRatio) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@78401262 (value: 1.6f)
[Randomization Seed](org-eclipse-elk-randomSeed) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@63a80706 (value: 1)
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) |  | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3c4398d6 (isTrue: true)
[Interactive](org-eclipse-elk-interactive) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@d6b0761 (isTrue: false) | 
[Port Constraints](org-eclipse-elk-portConstraints) | <XFeatureCallImplCustom>.UNDEFINED | 
[Force Model](org-eclipse-elk-force-model) | <XFeatureCallImplCustom>.FRUCHTERMAN_REINGOLD | 
[FR Temperature](org-eclipse-elk-force-temperature) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@5e3e2d94 (value: 0.001f) | 
[Iterations](org-eclipse-elk-force-iterations) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@6d04f92f (value: 300) | 
[Eades Repulsion](org-eclipse-elk-force-repulsion) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@606cbf12 (value: 5.0f) | 
[Repulsive Power](org-eclipse-elk-force-repulsivePower) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@364121b5 (value: 0) | 

