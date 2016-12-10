---
layout: page
title: Port Index
type: option
---
org.eclipse.elk.port.index

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: index
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: int
label: Port Index
description: The index of a port in the fixed order around a node. The order is assumed as clockwise,
			starting with the leftmost port on the top side. This option must be set if 'Port
			Constraints' is set to FIXED_ORDER and no specific positions are given for the ports.
			Additionally, the option 'Port Side' must be defined in this case.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [ports]
legady ids: [de.cau.cs.kieler.portIndex]
dependencies:

## Group(s)
port 

