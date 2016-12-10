---
layout: page
title: Edge Straightening
type: option
---
org.eclipse.elk.layered.nodePlacement.bk.edgeStraightening

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: edgeStraightening
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.alg.layered.p4nodes.bk.EdgeStraighteningStrategy
label: Edge Straightening
description: Specifies whether the Brandes Koepf node placer tries to increase the number of straight edges
                at the expense of diagram size.
documentation: 
default value: <XFeatureCallImplCustom>.IMPROVE_STRAIGHTNESS
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.nodeplace.compactionStrategy]
dependencies: (org.eclipse.elk.layered.nodePlacement.strategy == <XFeatureCallImplCustom>.BRANDES_KOEPF)

## Group(s)
nodePlacement bk 

