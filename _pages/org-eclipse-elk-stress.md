---
layout: page
title: ELK Stress
type: algorithm
---
**Identifier:** org.eclipse.elk.stress
**Meta Data Provider:** properties.StressMetaDataProvider

Minimizes the stress within a layout using stress majorization. Stress exists if the euclidean distance between a pair of nodes doesn't match their graph theoretic distance, that is, the shortest path between the two nodes. The method allows to specify individual edge lengths.

## Category: Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Interactive](org-eclipse-elk-interactive) | boolean | *not defined* | org.eclipse.elk.interactive
[Fixed Position](org-eclipse-elk-stress-fixed) | boolean | *not defined* | org.eclipse.elk.stress.fixed
[Layout Dimension](org-eclipse-elk-stress-dimension) | Dimension | *not defined* | org.eclipse.elk.stress.dimension
[Stress Epsilon](org-eclipse-elk-stress-epsilon) | float | *not defined* | org.eclipse.elk.stress.epsilon
[Iteration Limit](org-eclipse-elk-stress-iterationLimit) | int | *not defined* | org.eclipse.elk.stress.iterationLimit
[Desired Edge Length](org-eclipse-elk-stress-desiredEdgeLength) | float | *not defined* | org.eclipse.elk.stress.desiredEdgeLength

