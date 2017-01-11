---
layout: page
title: Edge Node Spacing Factor
type: option
---
org.eclipse.elk.layered.spacing.edgeNodeSpacingFactor

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: edgeNodeSpacingFactor
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: float
label: Edge Node Spacing Factor
description: Factor by which the object spacing is multiplied to arrive at the minimal spacing between
            an edge and a node.
documentation: 
default value:  0.5f
lower bound:  ExclusiveBounds.greaterThan(0)
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.edgeNodeSpacingFactor]
dependencies:

## Group(s)
spacing 

