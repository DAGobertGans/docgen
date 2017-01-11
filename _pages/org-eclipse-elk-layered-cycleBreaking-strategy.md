---
layout: page
title: Cycle Breaking Strategy
type: option
---
org.eclipse.elk.layered.cycleBreaking.strategy

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: strategy
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: org.eclipse.elk.alg.layered.p1cycles.CycleBreakingStrategy
label: Cycle Breaking Strategy
description: Strategy for cycle breaking. Cycle breaking looks for cycles in the graph and determines
            which edges to reverse to break the cycles. Reversed edges will end up pointing to the
            opposite direction of regular edges (that is, reversed edges will point left if edges
            usually point right).
documentation: 
default value:  CycleBreakingStrategy.GREEDY
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.cycleBreaking]
dependencies:

## Group(s)
cycleBreaking 

