---
layout: page
title: Sausage Folding
type: option
---
org.eclipse.elk.layered.sausageFolding

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: sausageFolding
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: boolean
label: Sausage Folding
description: Whether long sausages should be folded up nice and tight.
documentation: 
default value:  false
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.sausageFolding]
dependencies: (org.eclipse.elk.layered.layering.strategy == <XFeatureCallImplCustom>.LONGEST_PATH)

## Group(s)


