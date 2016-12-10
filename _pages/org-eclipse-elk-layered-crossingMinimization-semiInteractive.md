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
type: JvmParameterizedTypeReference: boolean
label: Semi-Interactive Crossing Minimization
description: Preserves the order of nodes within a layer but still minimizes 
			 crossings between edges connecting long edge dummies. 
			 Requires a crossing minimization strategy that is able to 
			 process 'in-layer' constraints.
documentation: 
default value: org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@560044b8 (isTrue: false)
lower bound: 
upper bound: 
targets: [parents]
legady ids: []
dependencies:

## Group(s)
crossingMinimization 

