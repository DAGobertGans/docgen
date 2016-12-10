---
layout: page
title: Junction Points
type: option
---
org.eclipse.elk.junctionPoints

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: junctionPoints
deprecated: false
advanced: false
programmatic: false
output: true
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.math.KVectorChain
label: Junction Points
description: This option is not used as option, but as output of the layout algorithms. It is
		attached to edges and determines the points where junction symbols should be drawn in
		order to represent hyperedges with orthogonal routing. Whether such points are computed
		depends on the chosen layout algorithm and edge routing style. The points are put into
		the vector chain with no specific order.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [edges]
legady ids: [de.cau.cs.kieler.junctionPoints]
dependencies:

## Group(s)


