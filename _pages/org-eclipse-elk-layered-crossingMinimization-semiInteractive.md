---
layout: page
title: Semi-Interactive Crossing Minimization
type: option
---
org.eclipse.elk.layered.crossingMinimization.semiInteractive

bundle.label: 
bundle.idPrefix: org.eclipse.elk.layered
bundle.targetClass: properties.LayeredMetaDataProvider
name: semiInteractive
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: boolean
label: Semi-Interactive Crossing Minimization
description: Preserves the order of nodes within a layer but still minimizes 
			 crossings between edges connecting long edge dummies. 
			 Requires a crossing minimization strategy that is able to 
			 process 'in-layer' constraints.
documentation: 
default value:  false
lower bound: *not defined*
upper bound: *not defined*
targets: [parents]
legady ids: []
dependencies:

## Group(s)
crossingMinimization 

