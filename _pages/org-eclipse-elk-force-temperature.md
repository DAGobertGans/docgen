---
layout: page
title: FR Temperature
type: option
---
org.eclipse.elk.force.temperature

bundle.label: 
bundle.idPrefix: org.eclipse.elk.force
bundle.targetClass: properties.ForceMetaDataProvider
name: temperature
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: float
label: FR Temperature
description: The temperature is used as a scaling factor for particle displacements.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@5e3e2d94 (value: 0.001f)
lower bound: <XFeatureCallImplCustom>.greaterThan(<XNumberLiteralImpl>)
upper bound: 
targets: [parents]
legady ids: []
dependencies: (org.eclipse.elk.force.model == <XFeatureCallImplCustom>.FRUCHTERMAN_REINGOLD)

## Group(s)


