---
layout: page
title: Port Side
type: option
---
org.eclipse.elk.port.side

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: side
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.options.PortSide
label: Port Side
description: The side of a node on which a port is situated. This option must be set if 'Port
			Constraints' is set to FIXED_SIDE or FIXED_ORDER and no specific positions are given
			for the ports.
documentation: 
default value: <XFeatureCallImplCustom>.UNDEFINED
lower bound: 
upper bound: 
targets: [ports]
legady ids: [de.cau.cs.kieler.portSide]
dependencies:

## Group(s)
port 

