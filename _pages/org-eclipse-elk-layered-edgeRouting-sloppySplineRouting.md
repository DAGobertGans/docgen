---
layout: page
title: Sloppy Spline Routing
type: option
---
org.eclipse.elk.layered.edgeRouting.sloppySplineRouting

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: sloppySplineRouting
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: boolean
label: Sloppy Spline Routing
description: Use less spline control points at the start and end of an edge. Might lead to crossings edge/node overlap.
documentation: 
default value:  true
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: []
dependencies: (org.eclipse.elk.edgeRouting == <XFeatureCallImplCustom>.SPLINES)

## Group(s)
edgeRouting 

