---
layout: page
title: BK Edge Straightening
type: option
---
advanced

**Identifier:** org.eclipse.elk.layered.nodePlacement.bk.edgeStraightening
**Meta Data Provider:** properties.LayeredMetaDataProvider
**Type:** org.eclipse.elk.alg.layered.p4nodes.bk.EdgeStraighteningStrategy
**Default Value:**  EdgeStraighteningStrategy.IMPROVE_STRAIGHTNESS  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Specifies whether the Brandes Koepf node placer tries to increase the number of straight edges at the expense of diagram size. There is a subtle difference to the 'favorStraightEdges' option, which decides whether a balanced placement of the nodes is desired, or not. In bk terms this means combining the four alignments into a single balanced one, or not. This option on the other hand tries to straighten additional edges during the creation of each of the four alignments.

**Legacy Id:** de.cau.cs.kieler.klay.layered.nodeplace.compactionStrategy
**Dependencies:** org.eclipse.elk.layered.nodePlacement.strategy
**Containing Groups:** [nodePlacement](org-eclipse-elk-layered-nodePlacement) -> [bk](org-eclipse-elk-layered-nodePlacement-bk)

