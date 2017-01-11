---
layout: page
title: Post Compaction Strategy
type: option
---
org.eclipse.elk.layered.compaction.postCompaction.strategy

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: strategy
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: org.eclipse.elk.alg.layered.intermediate.compaction.GraphCompactionStrategy
label: Post Compaction Strategy
description: Specifies whether and how post-process compaction is applied.
documentation: 
default value:  GraphCompactionStrategy.NONE
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.postCompaction]
dependencies:

## Group(s)
compaction postCompaction 

