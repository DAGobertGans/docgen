---
layout: page
title: Additional Port Space
type: option
---
org.eclipse.elk.spacing.portSurrounding

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: portSurrounding
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.util.nodespacing.Spacing$Margins
label: Additional Port Space
description: Additional space around the sets of ports on each node side. For each side of a node,
			this option can reserve additional space before and after the ports on each side. For
			example, a top spacing of 20 makes sure that the first port on the western and eastern
			side is 20 units away from the northern border.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [nodes]
legady ids: []
dependencies:

## Group(s)
spacing 

