---
layout: page
title: Box Layout Mode
type: option
---
org.eclipse.elk.box.packingMode

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: packingMode
deprecated: false
advanced: false
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.util.BoxLayoutProvider$PackingMode
label: Box Layout Mode
description: Configures the packing mode used by the {@link BoxLayoutProvider}.
             If SIMPLE is not required (neither priorities are used nor the interactive mode),
             GROUP_DEC can improve the packing and decrease the area. 
             GROUP_MIXED and GROUP_INC may, in very specific scenarios, work better.
documentation: 
default value: <XFeatureCallImplCustom>.SIMPLE
lower bound: 
upper bound: 
targets: [parents]
legady ids: []
dependencies:

## Group(s)
box 

