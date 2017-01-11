---
layout: page
title: High Degree Node Threshold
type: option
---
org.eclipse.elk.layered.highDegreeNodes.threshold

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: threshold
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: int
label: High Degree Node Threshold
description: Whether a node is considered to have a high degree.
documentation: 
default value:  16
lower bound:  0
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.highDegreeNode.threshold]
dependencies: (org.eclipse.elk.layered.highDegreeNodes.treatment == org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@1b779ec0 (isTrue: true))

## Group(s)
highDegreeNodes 

