---
layout: page
title: Layout Partition
type: option
---
org.eclipse.elk.partitioning.partition

bundle.label: ELK
bundle.idPrefix: org.eclipse.elk
bundle.targetClass: core.options.CoreOptions
name: partition
deprecated: false
advanced: true
programmatic: false
output: false
global: false
type: JvmParameterizedTypeReference: java.lang.Integer
label: Layout Partition
description: Partition to which the node belongs to. If 'layoutPartitions' is true,
			all nodes are expected to have a partition.
documentation: 
default value: 
lower bound: 
upper bound: 
targets: [parents, nodes]
legady ids: [de.cau.cs.kieler.partition]
dependencies:

## Group(s)
partitioning 

