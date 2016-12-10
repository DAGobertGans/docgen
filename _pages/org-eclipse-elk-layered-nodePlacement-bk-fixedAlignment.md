---
layout: page
title: Fixed Alignment
type: option
---
org.eclipse.elk.layered.nodePlacement.bk.fixedAlignment

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: fixedAlignment
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.alg.layered.properties.FixedAlignment
label: Fixed Alignment
description: Tells the BK node placer to use a certain alignment instead of taking the optimal result.
documentation: 
default value: <XFeatureCallImplCustom>.NONE
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.fixedAlignment]
dependencies: (org.eclipse.elk.layered.nodePlacement.strategy == <XFeatureCallImplCustom>.BRANDES_KOEPF)

## Group(s)
nodePlacement bk 

