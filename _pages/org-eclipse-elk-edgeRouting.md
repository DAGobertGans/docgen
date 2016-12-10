---
layout: page
title: Edge Routing
type: option
---
org.eclipse.elk.edgeRouting

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: edgeRouting
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.options.EdgeRouting
label: Edge Routing
description: What kind of edge routing style should be applied for the content of a parent node.
		Algorithms may also set this option to single edges in order to mark them as splines.
		The bend point list of edges with this option set to SPLINES must be interpreted as control
		points for a piecewise cubic spline.
documentation: 
default value: <XFeatureCallImplCustom>.UNDEFINED
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.edgeRouting]
dependencies:

## Group(s)


