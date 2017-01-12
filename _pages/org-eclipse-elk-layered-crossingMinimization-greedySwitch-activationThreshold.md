---
layout: page
title: Greedy Switch Activation Threshold
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.crossingMinimization.greedySwitch.activationThreshold
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** int
**Default Value:**  40  (not specific to an algorithm)
**Lower Bound:**  0
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
By default it is decided automatically if the greedy switch is activated or not. The decision is based on whether the size of the input graph (without dummy nodes) is smaller than the value of this option. A '0' enforces the activation.

**Containing Groups:** [crossingMinimization](org-eclipse-elk-layered-crossingMinimization) -> [greedySwitch](org-eclipse-elk-layered-crossingMinimization-greedySwitch)

