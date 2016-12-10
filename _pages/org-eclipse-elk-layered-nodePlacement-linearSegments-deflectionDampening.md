---
layout: page
title: Linear Segments Deflection Dampening
type: option
---
org.eclipse.elk.layered.nodePlacement.linearSegments.deflectionDampening

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: deflectionDampening
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: float
label: Linear Segments Deflection Dampening
description: Dampens the movement of nodes to keep the diagram from getting too large.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@42e159c4 (value: 0.3f)
lower bound: <XFeatureCallImplCustom>.greaterThan(<XNumberLiteralImpl>)
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.linearSegmentsDeflectionDampening]
dependencies: (org.eclipse.elk.layered.nodePlacement.strategy == <XFeatureCallImplCustom>.LINEAR_SEGMENTS)

## Group(s)
nodePlacement linearSegments 

