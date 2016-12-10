---
layout: page
title: Node Label Placement
type: option
---
org.eclipse.elk.nodeLabels.placement

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: placement
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: java.util.EnumSet<JvmParameterizedTypeReference: org.eclipse.elk.core.options.NodeLabelPlacement>
label: Node Label Placement
description: Hints for where node labels are to be placed; if empty, the node label's position is not
			modified.
documentation: 
default value: <XFeatureCallImplCustom>.fixed
lower bound: 
upper bound: 
targets: [nodes, labels]
legady ids: [de.cau.cs.kieler.nodeLabelPlacement]
dependencies:

## Group(s)
nodeLabels 

