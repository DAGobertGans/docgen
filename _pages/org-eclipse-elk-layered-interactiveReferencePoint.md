---
layout: page
title: Interactive Reference Point
type: option
---
org.eclipse.elk.layered.interactiveReferencePoint

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: interactiveReferencePoint
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: org.eclipse.elk.alg.layered.properties.InteractiveReferencePoint
label: Interactive Reference Point
description: Determines which point of a node is considered by interactive layout phases.
documentation: 
default value:  InteractiveReferencePoint.CENTER
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.interactiveReferencePoint]
dependencies: (org.eclipse.elk.layered.cycleBreaking.strategy == <XFeatureCallImplCustom>.INTERACTIVE) (org.eclipse.elk.layered.crossingMinimization.strategy == <XFeatureCallImplCustom>.INTERACTIVE)

## Group(s)


