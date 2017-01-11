---
layout: page
title: Layer Bound
type: option
---
org.eclipse.elk.layered.layering.coffmanGraham.layerBound

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: layerBound
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: int
label: Layer Bound
description: The maximum number of nodes allowed per layer.
documentation: 
default value:  Integer.MAX_VALUE
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: []
dependencies: (org.eclipse.elk.layered.layering.strategy == <XFeatureCallImplCustom>.COFFMAN_GRAHAM)

## Group(s)
layering coffmanGraham 

