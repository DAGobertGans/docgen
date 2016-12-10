---
layout: page
title: ELK Stress
type: algorithm
---
org.eclipse.elk.stress

Minimizes the stress within a layout using stress majorization.         Stress exists if the euclidean distance between a pair of          nodes doesn't match their graph theoretic distance, that is,          the shortest path between the two nodes.         The method allows to specify individual edge lengths.

## Meta Data Provider
properties.StressMetaDataProvider

## Category
### Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Interactive](org-eclipse-elk-interactive) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@d6b0761 (isTrue: false) | 
[Fixed Position](org-eclipse-elk-stress-fixed) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@4b8cf229 (isTrue: false) | 
[Layout Dimension](org-eclipse-elk-stress-dimension) | <XFeatureCallImplCustom>.XY | 
[Stress Epsilon](org-eclipse-elk-stress-epsilon) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1a403483 (value: 10e-4f) | 
[Iteration Limit](org-eclipse-elk-stress-iterationLimit) | <XFeatureCallImplCustom>.MAX_VALUE | 
[Desired Edge Length](org-eclipse-elk-stress-desiredEdgeLength) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@48dbc65f (value: 100f) | 

