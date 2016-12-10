---
layout: page
title: Port Border Offset
type: option
---
org.eclipse.elk.port.borderOffset

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: borderOffset
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: float
label: Port Border Offset
description: The offset of ports on the node border. With a positive offset the port is moved outside
			of the node, while with a negative offset the port is moved towards the inside. An offset
			of 0 means that the port is placed directly on the node border, i.e.
	     	if the port side is north, the port's south border touches the nodes's north border;
	     	if the port side is east, the port's west border touches the nodes's east border;
	     	if the port side is south, the port's north border touches the node's south border;
	     	if the port side is west, the port's east border touches the node's west border.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [ports]
legady ids: [de.cau.cs.kieler.offset]
dependencies:

## Group(s)
port 

