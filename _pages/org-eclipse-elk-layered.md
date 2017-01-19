---
layout: page
title: ELK Layered
type: algorithm
---
## ELK Layered
![](images/layered.png)
**Identifier:** org.eclipse.elk.layered
**Meta Data Provider:** properties.LayeredMetaDataProvider

Layer-based algorithm provided by the Eclipse Layout Kernel. Arranges as many edges as possible into one direction by placing nodes into subsequent layers. This implementation supports different routing styles (straight, orthogonal, splines); if orthogonal routing is selected, arbitrary port constraints are respected, thus enabling the layout of block diagrams such as actor-oriented models or circuit schematics. Furthermore, full layout of compound graphs with cross-hierarchy edges is supported when the respective option is activated on the top level.

## Category: Layered
The layer-based method was introduced by Sugiyama, Tagawa and Toda in 1981. It emphasizes the direction of edges by pointing as many edges as possible into the same direction. The nodes are arranged in layers, which are sometimes called "hierarchies", and then reordered such that the number of edge crossings is minimized. Afterwards, concrete coordinates are computed for the nodes and edge bend points.

## Supported Graph Features

Name | Description
----|----
Self Loops | Edges connecting a node with itself.
Inside Self Loops | Self-loops routed through a node instead of around it.
Multi Edges | Multiple edges with the same source and target node.
Edge Labels | Labels that are associated with edges.
Ports | Edges are connected to nodes over ports.
Compound | Edges that connect nodes from different hierarchy levels and are incident to compound nodes.
Clusters | Edges that connect nodes from different clusters, but not the cluster parent nodes.

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Activate Inside Self Loops](org-eclipse-elk-insideSelfLoops-activate) | `boolean` | `false` | org.eclipse.elk.insideSelfLoops.activate
[Add Unnecessary Bendpoints](org-eclipse-elk-layered-unnecessaryBendpoints) | `boolean` | `false` | org.eclipse.elk.layered.unnecessaryBendpoints
[Alignment](org-eclipse-elk-alignment) | `Alignment` | `Alignment.AUTOMATIC` | org.eclipse.elk.alignment
[Aspect Ratio](org-eclipse-elk-aspectRatio) | `double` | `1.6f` | org.eclipse.elk.aspectRatio
[BK Edge Straightening](org-eclipse-elk-layered-nodePlacement-bk-edgeStraightening) | `EdgeStraighteningStrategy` | `EdgeStraighteningStrategy.IMPROVE_STRAIGHTNESS` | org.eclipse.elk.layered.nodePlacement.bk.edgeStraightening
[BK Fixed Alignment](org-eclipse-elk-layered-nodePlacement-bk-fixedAlignment) | `FixedAlignment` | `FixedAlignment.NONE` | org.eclipse.elk.layered.nodePlacement.bk.fixedAlignment
[Comment Box](org-eclipse-elk-commentBox) | `boolean` | `false` | org.eclipse.elk.commentBox
[Components Spacing](org-eclipse-elk-spacing-componentComponent) | `double` | `12f` | org.eclipse.elk.spacing.componentComponent
[Connected Components Compaction](org-eclipse-elk-layered-compaction-connectedComponents) | `boolean` | `false` | org.eclipse.elk.layered.compaction.connectedComponents
[Content Alignment](org-eclipse-elk-layered-contentAlignment) | `EnumSet<ContentAlignment>` | `EnumSet.noneOf(ContentAlignment)` | org.eclipse.elk.layered.contentAlignment
[Crossing Minimization Strategy](org-eclipse-elk-layered-crossingMinimization-strategy) | `CrossingMinimizationStrategy` | `CrossingMinimizationStrategy.LAYER_SWEEP` | org.eclipse.elk.layered.crossingMinimization.strategy
[Cycle Breaking Strategy](org-eclipse-elk-layered-cycleBreaking-strategy) | `CycleBreakingStrategy` | `CycleBreakingStrategy.GREEDY` | org.eclipse.elk.layered.cycleBreaking.strategy
[Debug Mode](org-eclipse-elk-debugMode) | `boolean` | `false` | org.eclipse.elk.debugMode
[Direction](org-eclipse-elk-direction) | `Direction` | `Direction.UNDEFINED` | org.eclipse.elk.direction
[Direction Priority](org-eclipse-elk-layered-priority-direction) | `int` | `0` | org.eclipse.elk.layered.priority.direction
[Distribute Nodes (Deprecated)](org-eclipse-elk-layered-layering-distributeNodes) | `boolean` | `false` | org.eclipse.elk.layered.layering.distributeNodes
[Edge Edge Between Layer Spacing](org-eclipse-elk-layered-spacing-edgeEdgeBetweenLayers) | `double` | `10` | org.eclipse.elk.layered.spacing.edgeEdgeBetweenLayers
[Edge Label Placement](org-eclipse-elk-edgeLabels-placement) | `EdgeLabelPlacement` | `EdgeLabelPlacement.UNDEFINED` | org.eclipse.elk.edgeLabels.placement
[Edge Label Placement Strategy](org-eclipse-elk-layered-edgeCenterLabelPlacementStrategy) | `EdgeLabelPlacementStrategy` | `EdgeLabelPlacementStrategy.CENTER` | org.eclipse.elk.layered.edgeCenterLabelPlacementStrategy
[Edge Label Side Selection](org-eclipse-elk-layered-edgeLabelSideSelection) | `EdgeLabelSideSelection` | `EdgeLabelSideSelection.ALWAYS_DOWN` | org.eclipse.elk.layered.edgeLabelSideSelection
[Edge Label Spacing](org-eclipse-elk-spacing-edgeLabel) | `double` | `5` | org.eclipse.elk.spacing.edgeLabel
[Edge Node Between Layers Spacing](org-eclipse-elk-layered-spacing-edgeNodeBetweenLayers) | `double` | `10` | org.eclipse.elk.layered.spacing.edgeNodeBetweenLayers
[Edge Node Spacing](org-eclipse-elk-spacing-edgeNode) | `double` | `10` | org.eclipse.elk.spacing.edgeNode
[Edge Routing](org-eclipse-elk-edgeRouting) | `EdgeRouting` | `EdgeRouting.ORTHOGONAL` | org.eclipse.elk.edgeRouting
[Edge Spacing](org-eclipse-elk-spacing-edgeEdge) | `double` | `10` | org.eclipse.elk.spacing.edgeEdge
[Edge Thickness](org-eclipse-elk-edge-thickness) | `double` | `1` | org.eclipse.elk.edge.thickness
[Favor Straight Edges Over Balancing](org-eclipse-elk-layered-nodePlacement-favorStraightEdges) | `boolean` | `*not defined*` | org.eclipse.elk.layered.nodePlacement.favorStraightEdges
[Feedback Edges](org-eclipse-elk-layered-feedbackEdges) | `boolean` | `false` | org.eclipse.elk.layered.feedbackEdges
[Greedy Switch Activation Threshold](org-eclipse-elk-layered-crossingMinimization-greedySwitch-activationThreshold) | `int` | `40` | org.eclipse.elk.layered.crossingMinimization.greedySwitch.activationThreshold
[Greedy Switch Crossing Minimization](org-eclipse-elk-layered-crossingMinimization-greedySwitch-type) | `GreedySwitchType` | `GreedySwitchType.TWO_SIDED` | org.eclipse.elk.layered.crossingMinimization.greedySwitch.type
[Hierarchical Sweepiness](org-eclipse-elk-layered-crossingMinimization-hierarchicalSweepiness) | `double` | `0.1` | org.eclipse.elk.layered.crossingMinimization.hierarchicalSweepiness
[Hierarchy Handling](org-eclipse-elk-hierarchyHandling) | `HierarchyHandling` | `HierarchyHandling.INHERIT` | org.eclipse.elk.hierarchyHandling
[High Degree Node Maximum Tree Height](org-eclipse-elk-layered-highDegreeNodes-treeHeight) | `int` | `5` | org.eclipse.elk.layered.highDegreeNodes.treeHeight
[High Degree Node Threshold](org-eclipse-elk-layered-highDegreeNodes-threshold) | `int` | `16` | org.eclipse.elk.layered.highDegreeNodes.threshold
[High Degree Node Treatment](org-eclipse-elk-layered-highDegreeNodes-treatment) | `boolean` | `false` | org.eclipse.elk.layered.highDegreeNodes.treatment
[Hypernode](org-eclipse-elk-hypernode) | `boolean` | `false` | org.eclipse.elk.hypernode
[Individual Spacing Override](org-eclipse-elk-spacing-individualOverride(org.eclipse.elk.layered)) | `IndividualSpacings` | `*not defined*` | org.eclipse.elk.spacing.individualOverride
[Inside Self Loop](org-eclipse-elk-insideSelfLoops-yo) | `boolean` | `false` | org.eclipse.elk.insideSelfLoops.yo
[Interactive Reference Point](org-eclipse-elk-layered-interactiveReferencePoint) | `InteractiveReferencePoint` | `InteractiveReferencePoint.CENTER` | org.eclipse.elk.layered.interactiveReferencePoint
[Junction Points](org-eclipse-elk-junctionPoints) | `KVectorChain` | `new KVectorChain()` | org.eclipse.elk.junctionPoints
[Label Node Spacing](org-eclipse-elk-spacing-labelNode) | `double` | `5` | org.eclipse.elk.spacing.labelNode
[Label Port Spacing](org-eclipse-elk-spacing-labelPort) | `double` | `5` | org.eclipse.elk.spacing.labelPort
[Label Spacing](org-eclipse-elk-spacing-labelLabel) | `double` | `0` | org.eclipse.elk.spacing.labelLabel
[Layer Bound](org-eclipse-elk-layered-layering-coffmanGraham-layerBound) | `int` | `Integer.MAX_VALUE` | org.eclipse.elk.layered.layering.coffmanGraham.layerBound
[Layer Constraint](org-eclipse-elk-layered-layering-layerConstraint) | `LayerConstraint` | `LayerConstraint.NONE` | org.eclipse.elk.layered.layering.layerConstraint
[Layout Hierarchy](org-eclipse-elk-layoutHierarchy) | `boolean` | `false` | org.eclipse.elk.layoutHierarchy
[Layout Partition](org-eclipse-elk-partitioning-partition) | `Integer` | `*not defined*` | org.eclipse.elk.partitioning.partition
[Layout Partitioning](org-eclipse-elk-partitioning-activate) | `Boolean` | `false` | org.eclipse.elk.partitioning.activate
[Linear Segments Deflection Dampening](org-eclipse-elk-layered-nodePlacement-linearSegments-deflectionDampening) | `double` | `0.3` | org.eclipse.elk.layered.nodePlacement.linearSegments.deflectionDampening
[Margins](org-eclipse-elk-margins) | `ElkMargin` | `new ElkMargin()` | org.eclipse.elk.margins
[Max Node Promotion Iterations](org-eclipse-elk-layered-layering-nodePromotion-maxIterations) | `int` | `0` | org.eclipse.elk.layered.layering.nodePromotion.maxIterations
[Merge Edges](org-eclipse-elk-layered-mergeEdges) | `boolean` | `false` | org.eclipse.elk.layered.mergeEdges
[Merge Hierarchy-Crossing Edges](org-eclipse-elk-layered-mergeHierarchyEdges) | `boolean` | `true` | org.eclipse.elk.layered.mergeHierarchyEdges
[Minimum Height](org-eclipse-elk-nodeSize-minHeight) | `double` | `0` | org.eclipse.elk.nodeSize.minHeight
[Minimum Width](org-eclipse-elk-nodeSize-minWidth) | `double` | `0` | org.eclipse.elk.nodeSize.minWidth
[No Layout](org-eclipse-elk-noLayout) | `boolean` | `false` | org.eclipse.elk.noLayout
[Node Label Placement](org-eclipse-elk-nodeLabels-placement) | `EnumSet<NodeLabelPlacement>` | `NodeLabelPlacement.fixed` | org.eclipse.elk.nodeLabels.placement
[Node Layering Strategy](org-eclipse-elk-layered-layering-strategy) | `LayeringStrategy` | `LayeringStrategy.NETWORK_SIMPLEX` | org.eclipse.elk.layered.layering.strategy
[Node Node Between Layers Spacing](org-eclipse-elk-layered-spacing-nodeNodeBetweenLayers) | `double` | `20` | org.eclipse.elk.layered.spacing.nodeNodeBetweenLayers
[Node Placement Strategy](org-eclipse-elk-layered-nodePlacement-strategy) | `NodePlacementStrategy` | `NodePlacementStrategy.BRANDES_KOEPF` | org.eclipse.elk.layered.nodePlacement.strategy
[Node Promotion Strategy](org-eclipse-elk-layered-layering-nodePromotion-strategy) | `NodePromotionStrategy` | `NodePromotionStrategy.NONE` | org.eclipse.elk.layered.layering.nodePromotion.strategy
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | `EnumSet<SizeConstraint>` | `EnumSet.noneOf(SizeConstraint)` | org.eclipse.elk.nodeSize.constraints
[Node Size Minimum](org-eclipse-elk-nodeSize-minimum) | `KVector` | `*not defined*` | org.eclipse.elk.nodeSize.minimum
[Node Size Options](org-eclipse-elk-nodeSize-options) | `EnumSet<SizeOptions>` | `EnumSet.of(SizeOptions.DEFAULT_MINIMUM_SIZE, SizeOptions.APPLY_ADDITIONAL_PADDING)` | org.eclipse.elk.nodeSize.options
[Node Spacing](org-eclipse-elk-spacing-nodeNode) | `double` | `20` | org.eclipse.elk.spacing.nodeNode
[North or South Port](org-eclipse-elk-layered-northOrSouthPort) | `boolean` | `false` | org.eclipse.elk.layered.northOrSouthPort
[Padding](org-eclipse-elk-padding) | `ElkPadding` | `new ElkPadding(12)` | org.eclipse.elk.padding
[Port Alignment](org-eclipse-elk-portAlignment-basic) | `PortAlignment` | `PortAlignment.JUSTIFIED` | org.eclipse.elk.portAlignment.basic
[Port Alignment (East)](org-eclipse-elk-portAlignment-east) | `PortAlignment` | `PortAlignment.UNDEFINED` | org.eclipse.elk.portAlignment.east
[Port Alignment (North)](org-eclipse-elk-portAlignment-north) | `PortAlignment` | `PortAlignment.UNDEFINED` | org.eclipse.elk.portAlignment.north
[Port Alignment (South)](org-eclipse-elk-portAlignment-south) | `PortAlignment` | `PortAlignment.UNDEFINED` | org.eclipse.elk.portAlignment.south
[Port Alignment (West)](org-eclipse-elk-portAlignment-west) | `PortAlignment` | `PortAlignment.UNDEFINED` | org.eclipse.elk.portAlignment.west
[Port Anchor Offset](org-eclipse-elk-port-anchor) | `KVector` | `*not defined*` | org.eclipse.elk.port.anchor
[Port Border Offset](org-eclipse-elk-port-borderOffset) | `double` | `0` | org.eclipse.elk.port.borderOffset
[Port Constraints](org-eclipse-elk-portConstraints) | `PortConstraints` | `PortConstraints.UNDEFINED` | org.eclipse.elk.portConstraints
[Port Index](org-eclipse-elk-port-index) | `int` | `*not defined*` | org.eclipse.elk.port.index
[Port Label Placement](org-eclipse-elk-portLabels-placement) | `PortLabelPlacement` | `PortLabelPlacement.OUTSIDE` | org.eclipse.elk.portLabels.placement
[Port Side](org-eclipse-elk-port-side) | `PortSide` | `PortSide.UNDEFINED` | org.eclipse.elk.port.side
[Port Spacing](org-eclipse-elk-spacing-portPort) | `double` | `10` | org.eclipse.elk.spacing.portPort
[Position](org-eclipse-elk-position) | `KVector` | `*not defined*` | org.eclipse.elk.position
[Post Compaction Constraint Calculation](org-eclipse-elk-layered-compaction-postCompaction-constraints) | `ConstraintCalculationStrategy` | `ConstraintCalculationStrategy.SCANLINE` | org.eclipse.elk.layered.compaction.postCompaction.constraints
[Post Compaction Strategy](org-eclipse-elk-layered-compaction-postCompaction-strategy) | `GraphCompactionStrategy` | `GraphCompactionStrategy.NONE` | org.eclipse.elk.layered.compaction.postCompaction.strategy
[Priority](org-eclipse-elk-priority(org.eclipse.elk.layered)) | `int` | `0` | org.eclipse.elk.priority
[Randomization Seed](org-eclipse-elk-randomSeed) | `int` | `1` | org.eclipse.elk.randomSeed
[Sausage Folding](org-eclipse-elk-layered-sausageFolding) | `boolean` | `false` | org.eclipse.elk.layered.sausageFolding
[Semi-Interactive Crossing Minimization](org-eclipse-elk-layered-crossingMinimization-semiInteractive) | `boolean` | `false` | org.eclipse.elk.layered.crossingMinimization.semiInteractive
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) | `boolean` | `true` | org.eclipse.elk.separateConnectedComponents
[Shortness Priority](org-eclipse-elk-layered-priority-shortness(org.eclipse.elk.layered)) | `int` | `0` | org.eclipse.elk.layered.priority.shortness
[Sloppy Spline Layer Spacing Factor](org-eclipse-elk-layered-edgeRouting-sloppySplineLayerSpacing) | `double` | `0.4` | org.eclipse.elk.layered.edgeRouting.sloppySplineLayerSpacing
[Sloppy Spline Routing](org-eclipse-elk-layered-edgeRouting-sloppySplineRouting) | `boolean` | `true` | org.eclipse.elk.layered.edgeRouting.sloppySplineRouting
[Spline Self-Loop Placement](org-eclipse-elk-layered-edgeRouting-selfLoopPlacement) | `SelfLoopPlacement` | `SelfLoopPlacement.NORTH_STACKED` | org.eclipse.elk.layered.edgeRouting.selfLoopPlacement
[Straightness Priority](org-eclipse-elk-layered-priority-straightness) | `int` | `0` | org.eclipse.elk.layered.priority.straightness
[Thoroughness](org-eclipse-elk-layered-thoroughness) | `int` | `7` | org.eclipse.elk.layered.thoroughness
[Upper Bound On Width [MinWidth Layerer]](org-eclipse-elk-layered-layering-minWidth-upperBoundOnWidth) | `int` | `4` | org.eclipse.elk.layered.layering.minWidth.upperBoundOnWidth
[Upper Layer Estimation Scaling Factor [MinWidth Layerer]](org-eclipse-elk-layered-layering-minWidth-upperLayerEstimationScalingFactor) | `int` | `2` | org.eclipse.elk.layered.layering.minWidth.upperLayerEstimationScalingFactor
[Wide Nodes on Multiple Layers](org-eclipse-elk-layered-layering-wideNodesOnMultipleLayers) | `WideNodesStrategy` | `WideNodesStrategy.OFF` | org.eclipse.elk.layered.layering.wideNodesOnMultipleLayers

## Additional Documentation

test
