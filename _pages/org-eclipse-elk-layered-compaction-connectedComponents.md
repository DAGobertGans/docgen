---
layout: page
title: Connected Components Compaction
type: option
---
org.eclipse.elk.layered.compaction.connectedComponents

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: connectedComponents
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: boolean
label: Connected Components Compaction
description: Tries to further compact components (disconnected sub-graphs).
documentation: 
default value:  false
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.components.compact]
dependencies: (org.eclipse.elk.separateConnectedComponents == org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@632c46cb (isTrue: true))

## Group(s)
compaction 

