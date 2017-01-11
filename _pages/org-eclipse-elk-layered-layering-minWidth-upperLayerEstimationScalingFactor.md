---
layout: page
title: Upper Layer Estimation Scaling Factor [MinWidth Layerer]
type: option
---
org.eclipse.elk.layered.layering.minWidth.upperLayerEstimationScalingFactor

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: upperLayerEstimationScalingFactor
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: int
label: Upper Layer Estimation Scaling Factor [MinWidth Layerer]
description: Multiplied with Upper Bound On Width for defining an upper bound on the width of layers which
                haven't been determined yet, but whose maximum width had been (roughly) estimated by the MinWidth
                algorithm. Compensates for too high estimations.
documentation: 
default value:  2
lower bound:  1
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.minWidthUpperLayerEstimationScalingFactor]
dependencies: (org.eclipse.elk.layered.layering.strategy == <XFeatureCallImplCustom>.EXP_MIN_WIDTH)

## Group(s)
layering minWidth 

