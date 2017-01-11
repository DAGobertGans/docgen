---
layout: page
title: Node Promotion Strategy
type: option
---
org.eclipse.elk.layered.layering.nodePromotion.strategy

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: strategy
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: org.eclipse.elk.alg.layered.intermediate.NodePromotionStrategy
label: Node Promotion Strategy
description: Reduces number of dummy nodes after layering phase (if possible).
documentation: 
default value:  NodePromotionStrategy.NONE
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: [de.cau.cs.kieler.klay.layered.nodePromotion]
dependencies:

## Group(s)
layering nodePromotion 

