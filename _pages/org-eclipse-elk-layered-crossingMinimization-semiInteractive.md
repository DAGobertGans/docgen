---
layout: page
title: Semi-Interactive Crossing Minimization
type: option
---
## Semi-Interactive Crossing Minimization

----|----
**Type:** | advanced
**Identifier:** | org.eclipse.elk.layered.crossingMinimization.semiInteractive
**Meta Data Provider:** | properties.LayeredMetaDataProvider
**Value Type:** | `boolean`
**Default Value:** | `false` (as defined in org.eclipse.elk.layered)
**Applies To:** | parents
**Containing Groups:** | [crossingMinimization](org-eclipse-elk-layered-crossingMinimization)


### Description
Preserves the order of nodes within a layer but still minimizes crossings between edges connecting long edge dummies. Requires a crossing minimization strategy that is able to process 'in-layer' constraints.

