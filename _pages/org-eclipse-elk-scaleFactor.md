---
layout: page
title: Scale Factor
type: option
---
org.eclipse.elk.scaleFactor

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: scaleFactor
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: float
label: Scale Factor
description: The scaling factor to be applied to the corresponding node in recursive layout. It causes
		the corresponding node's size to be adjusted, and its ports and labels to be sized and
		placed accordingly after the layout of that node has been determined (and before the node
		itself and its siblings are arranged). The scaling is not reverted afterwards, so the
		resulting layout graph contains the adjusted size and position data. This option is
		currently not supported if 'Layout Hierarchy' is set.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@56ca624d (value: 1)
lower bound: <XFeatureCallImplCustom>.greaterThan(<XNumberLiteralImpl>)
upper bound: 
targets: [nodes]
legady ids: [de.cau.cs.kieler.scaleFactor]
dependencies: (org.eclipse.elk.layoutHierarchy == org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@162a3b71 (isTrue: false))

## Group(s)


