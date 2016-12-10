---
layout: page
title: Activate Inside Self Loops
type: option
---
org.eclipse.elk.insideSelfLoops.activate

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: activate
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: boolean
label: Activate Inside Self Loops
description: Whether this node allows to route self loops inside of it instead of around it. If set to true,
			this will make the node a compound node if it isn't already, and will require the layout algorithm
			to support compound nodes with hierarchical ports.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@e521db1 (isTrue: false)
lower bound: 
upper bound: 
targets: [nodes]
legady ids: [de.cau.cs.kieler.selfLoopInside]
dependencies:

## Group(s)
insideSelfLoops 

