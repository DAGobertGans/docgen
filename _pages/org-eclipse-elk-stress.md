---
layout: page
title: ELK Stress
type: algorithm
---
## ELK Stress
**Identifier:** org.eclipse.elk.stress
**Meta Data Provider:** properties.StressMetaDataProvider

Minimizes the stress within a layout using stress majorization. Stress exists if the euclidean distance between a pair of nodes doesn't match their graph theoretic distance, that is, the shortest path between the two nodes. The method allows to specify individual edge lengths.

## Category: Force
Layout algorithms that follow physical analogies by simulating a system of attractive and repulsive forces. The first successful method of this kind was proposed by Eades in 1984.

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Desired Edge Length](org-eclipse-elk-stress-desiredEdgeLength) | `float` | `100f` | org.eclipse.elk.stress.desiredEdgeLength
[Fixed Position](org-eclipse-elk-stress-fixed) | `boolean` | `false` | org.eclipse.elk.stress.fixed
[Interactive](org-eclipse-elk-interactive) | `boolean` | `false` | org.eclipse.elk.interactive
[Iteration Limit](org-eclipse-elk-stress-iterationLimit) | `int` | `Integer.MAX_VALUE` | org.eclipse.elk.stress.iterationLimit
[Layout Dimension](org-eclipse-elk-stress-dimension) | `Dimension` | `Dimension.XY` | org.eclipse.elk.stress.dimension
[Stress Epsilon](org-eclipse-elk-stress-epsilon) | `float` | `10e-4f` | org.eclipse.elk.stress.epsilon

