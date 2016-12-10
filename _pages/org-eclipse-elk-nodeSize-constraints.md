---
layout: page
title: Node Size Constraints
type: option
---
org.eclipse.elk.nodeSize.constraints

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: constraints
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: java.util.EnumSet<JvmParameterizedTypeReference: org.eclipse.elk.core.options.SizeConstraint>
label: Node Size Constraints
description: Constraints for determining node sizes. Each member of the set specifies something that
			should be taken into account when calculating node sizes. The empty set corresponds to
			node sizes being fixed.
documentation: 
default value: <XFeatureCallImplCustom>.noneOf(<XFeatureCallImplCustom>)
lower bound: 
upper bound: 
targets: [nodes]
legady ids: []
dependencies:

## Group(s)
nodeSize 

