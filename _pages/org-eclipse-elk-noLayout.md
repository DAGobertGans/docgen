---
layout: page
title: No Layout
type: option
---
org.eclipse.elk.noLayout

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: noLayout
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: boolean
label: No Layout
description: No layout is done for the associated element. This is used to mark parts of a diagram to
		avoid their inclusion in the layout graph, or to mark parts of the layout graph to
		prevent layout engines from processing them. If you wish to exclude the contents of a
		compound node from automatic layout, while the node itself is still considered on its own
		layer, use the 'Fixed Layout' algorithm for that node.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@69c3fd82 (isTrue: false)
lower bound: 
upper bound: 
targets: [nodes, edges, ports, labels]
legady ids: [de.cau.cs.kieler.noLayout]
dependencies:

## Group(s)


