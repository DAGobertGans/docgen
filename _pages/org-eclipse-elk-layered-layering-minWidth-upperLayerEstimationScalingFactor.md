---
layout: page
title: Upper Layer Estimation Scaling Factor [MinWidth Layerer]
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.layering.minWidth.upperLayerEstimationScalingFactor
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** int
**Default Value:**  2  (not specific to an algorithm)
**Lower Bound:**  1
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Multiplied with Upper Bound On Width for defining an upper bound on the width of layers which haven't been determined yet, but whose maximum width had been (roughly) estimated by the MinWidth algorithm. Compensates for too high estimations.

**Legacy Id:** de.cau.cs.kieler.klay.layered.minWidthUpperLayerEstimationScalingFactor
**Dependencies:** org.eclipse.elk.layered.layering.strategy
**Containing Groups:** [layering](org-eclipse-elk-layered-layering) -> [minWidth](org-eclipse-elk-layered-layering-minWidth)

