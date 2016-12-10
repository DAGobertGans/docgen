---
layout: page
title: Layout Hierarchy
type: option
---
org.eclipse.elk.layoutHierarchy

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: layoutHierarchy
deprecated: true
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: boolean
label: Layout Hierarchy
description: Whether the whole hierarchy shall be layouted. If this option is not set, each hierarchy
		level of the graph is processed independently, possibly by different layout algorithms,
		beginning with the lowest level. If it is set, the algorithm is responsible to process
		all hierarchy levels that are contained in the associated parent node.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@24704ef0 (isTrue: false)
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.layoutHierarchy]
dependencies:

## Group(s)


