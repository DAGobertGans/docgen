---
layout: page
title: Label Manager
type: option
---
org.eclipse.elk.labels.labelManager

bundle.label: ELK Label Management
bundle.idPrefix: org.eclipse.elk.labels
bundle.targetClass: LabelManagementOptions
name: labelManager
deprecated: false
advanced: false
programmatic: true
output: false
global: false
type: JvmParameterizedTypeReference: org.eclipse.elk.core.labels.ILabelManager
label: Label Manager
description: The label manager responsible for a given part of the graph. A label manager can either be
         attached to a compound node (in which case it is responsible for all labels inside) or to
         specific labels. The label manager can then be called by layout algorithms to modify labels
         that are too wide to try and shorten them to a given target width.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [parents, labels]
legady ids: []
dependencies:

## Group(s)


