---
layout: page
title: Bend Points
type: option
---
org.eclipse.elk.bendPoints

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: bendPoints
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.math.KVectorChain
label: Bend Points
description: A fixed list of bend points for the edge. This is used by the 'Fixed Layout' algorithm to
		specify a pre-defined routing for an edge. The vector chain must include the source point,
		any bend points, and the target point, so it must have at least two points.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [edges]
legady ids: [de.cau.cs.kieler.bendPoints]
dependencies:

## Group(s)


