---
layout: page
title: Node Size Options
type: option
---
org.eclipse.elk.nodeSize.options

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: options
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: java.util.EnumSet<JvmParameterizedTypeReference: org.eclipse.elk.core.options.SizeOptions>
label: Node Size Options
description: Options modifying the behavior of the size constraints set on a node. Each member of the
			set specifies something that should be taken into account when calculating node sizes.
			The empty set corresponds to no further modifications.
documentation: 
default value: <XFeatureCallImplCustom>.of(<XMemberFeatureCallImplCustom>,<XMemberFeatureCallImplCustom>)
lower bound: 
upper bound: 
targets: [nodes]
legady ids: []
dependencies:

## Group(s)
nodeSize 

