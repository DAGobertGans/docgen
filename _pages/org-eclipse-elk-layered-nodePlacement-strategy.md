---
layout: page
title: Node Placement Strategy
type: option
---
org.eclipse.elk.layered.nodePlacement.strategy

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: strategy
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.alg.layered.p4nodes.NodePlacementStrategy
label: Node Placement Strategy
description: Strategy for node placement.
documentation: ../additional-documentation/NodePlacementStrategy.md
default value: <XFeatureCallImplCustom>.BRANDES_KOEPF
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.nodePlacement]
dependencies:

## Group(s)
nodePlacement 

## Additional Documentation
(copied from confluence)
## Extra

Decides which algorithm is used to compute the y coordinate of each node. This influences the length of edges, the number of edge bends, and the height of the diagram. We have different algorithms available, with different optimization goals.

## Possible Values

* BRANDES_KOEPF
    Minimizes the number of edge bends at the expense of diagram size: diagrams drawn with this algorithm are usually higher than diagrams drawn with other algorithms.
* LINEAR_SEGMENTS
    Computes a balanced placement.
* INTERACTIVE
    Tries to keep the preset y coordinates of nodes from the original layout. For dummy nodes, a guess is made to infer their coordinates. Requires the other interactive phase implementations to have run as well.
* SIMPLE
    Minimizes the area at the expense of... well, pretty much everything else.
