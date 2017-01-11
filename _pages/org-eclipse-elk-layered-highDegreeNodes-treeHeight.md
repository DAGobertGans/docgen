---
layout: page
title: High Degree Node Maximum Tree Height
type: option
---
org.eclipse.elk.layered.highDegreeNodes.treeHeight

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: treeHeight
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: int
label: High Degree Node Maximum Tree Height
description: Maximum height of a subtree connected to a high degree node to be moved to separate layers.
documentation: 
default value:  5
lower bound:  0
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.highDegreeNode.treeHeight]
dependencies: (org.eclipse.elk.layered.highDegreeNodes.treatment == org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3087b061 (isTrue: true))

## Group(s)
highDegreeNodes 

