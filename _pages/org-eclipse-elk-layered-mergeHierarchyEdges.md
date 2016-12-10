---
layout: page
title: Merge Hierarchy-Crossing Edges
type: option
---
org.eclipse.elk.layered.mergeHierarchyEdges

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: mergeHierarchyEdges
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: boolean
label: Merge Hierarchy-Crossing Edges
description: If hierarchical layout is active, hierarchy-crossing edges use as few hierarchical ports
		as possible. They are broken by the algorithm, with hierarchical ports inserted as
		required. Usually, one such port is created for each edge at each hierarchy crossing point.
		With this option set to true, we try to create as few hierarchical ports as possible in
		the process. In particular, all edges that form a hyperedge can share a port.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@57a7efe2 (isTrue: true)
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.mergeHierarchyEdges]
dependencies:

## Group(s)


