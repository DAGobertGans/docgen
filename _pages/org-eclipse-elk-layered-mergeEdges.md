---
layout: page
title: Merge Edges
type: option
---
org.eclipse.elk.layered.mergeEdges

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: mergeEdges
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: boolean
label: Merge Edges
description: Edges that have no ports are merged so they touch the connected nodes at the same points.
		When this option is disabled, one port is created for each edge directly connected to a
		node. When it is enabled, all such incoming edges share an input port, and all outgoing
		edges share an output port.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@22b84bf7 (isTrue: false)
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.mergeEdges]
dependencies:

## Group(s)


