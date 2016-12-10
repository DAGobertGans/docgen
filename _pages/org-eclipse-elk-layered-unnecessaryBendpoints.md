---
layout: page
title: Add Unnecessary Bendpoints
type: option
---
org.eclipse.elk.layered.unnecessaryBendpoints

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: unnecessaryBendpoints
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: boolean
label: Add Unnecessary Bendpoints
description: Adds bend points even if an edge does not change direction. If true, each long edge dummy
		will contribute a bend point to its edges and hierarchy-crossing edges will always get a
		bend point where they cross hierarchy boundaries. By default, bend points are only added
		where an edge changes direction.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@67af3bee (isTrue: false)
lower bound: 
upper bound: 
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.unnecessaryBendpoints]
dependencies:

## Group(s)


