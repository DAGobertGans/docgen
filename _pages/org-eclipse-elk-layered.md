---
layout: page
title: ELK Layered
type: algorithm
---
**Identifier:** org.eclipse.elk.layered
**Meta Data Provider:** properties.LayeredMetaDataProvider

Layer-based algorithm provided by the Eclipse Layout Kernel. Arranges as many edges as possible into one direction by placing nodes into subsequent layers. This implementation supports different routing styles (straight, orthogonal, splines); if orthogonal routing is selected, arbitrary port constraints are respected, thus enabling the layout of block diagrams such as actor-oriented models or circuit schematics. Furthermore, full layout of compound graphs with cross-hierarchy edges is supported when the respective option is activated on the top level.

### Preview
![](images/layered.png)

## Category: Layered
The layer-based method was introduced by Sugiyama, Tagawa and Toda in 1981. It emphasizes the direction of edges by pointing as many edges as possible into the same direction. The nodes are arranged in layers, which are sometimes called "hierarchies", and then reordered such that the number of edge crossings is minimized. Afterwards, concrete coordinates are computed for the nodes and edge bend points.

## Supported Graph Features
SELF_LOOPS
INSIDE_SELF_LOOPS
MULTI_EDGES
EDGE_LABELS
PORTS
COMPOUND
CLUSTERS

## Supported Options

Option | Type | Default Value | Identifier
----|----|----
[Node Spacing](org-eclipse-elk-spacing-node) | float |  20 | org.eclipse.elk.spacing.node
[Border Spacing](org-eclipse-elk-spacing-border) | float |  12 | org.eclipse.elk.spacing.border
[Port Spacing](org-eclipse-elk-spacing-port) | float | *not defined* | org.eclipse.elk.spacing.port
[Label Spacing](org-eclipse-elk-spacing-label) | float | *not defined* | org.eclipse.elk.spacing.label
[Priority](org-eclipse-elk-priority) | int |  0 | org.eclipse.elk.priority
[Edge Routing](org-eclipse-elk-edgeRouting) | EdgeRouting |  EdgeRouting.ORTHOGONAL | org.eclipse.elk.edgeRouting
[Port Border Offset](org-eclipse-elk-port-borderOffset) | float |  0 | org.eclipse.elk.port.borderOffset
[Randomization Seed](org-eclipse-elk-randomSeed) | int |  1 | org.eclipse.elk.randomSeed
[Aspect Ratio](org-eclipse-elk-aspectRatio) | float |  1.6f | org.eclipse.elk.aspectRatio
[No Layout](org-eclipse-elk-noLayout) | boolean | *not defined* | org.eclipse.elk.noLayout
[Port Constraints](org-eclipse-elk-portConstraints) | PortConstraints | *not defined* | org.eclipse.elk.portConstraints
[Port Side](org-eclipse-elk-port-side) | PortSide | *not defined* | org.eclipse.elk.port.side
[Debug Mode](org-eclipse-elk-debugMode) | boolean | *not defined* | org.eclipse.elk.debugMode
[Alignment](org-eclipse-elk-alignment) | Alignment | *not defined* | org.eclipse.elk.alignment
[Layout Hierarchy](org-eclipse-elk-layoutHierarchy) | boolean | *not defined* | org.eclipse.elk.layoutHierarchy
[Hierarchy Handling](org-eclipse-elk-hierarchyHandling) | HierarchyHandling | *not defined* | org.eclipse.elk.hierarchyHandling
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) | boolean |  true | org.eclipse.elk.separateConnectedComponents
[Activate Inside Self Loops](org-eclipse-elk-insideSelfLoops-activate) | boolean | *not defined* | org.eclipse.elk.insideSelfLoops.activate
[Inside Self Loop](org-eclipse-elk-insideSelfLoops-yo) | boolean | *not defined* | org.eclipse.elk.insideSelfLoops.yo
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | EnumSet&lt;SizeConstraint&gt; | *not defined* | org.eclipse.elk.nodeSize.constraints
[Node Size Options](org-eclipse-elk-nodeSize-options) | EnumSet&lt;SizeOptions&gt; | *not defined* | org.eclipse.elk.nodeSize.options
[Direction](org-eclipse-elk-direction) | Direction |  Direction.UNDEFINED | org.eclipse.elk.direction
[Node Label Placement](org-eclipse-elk-nodeLabels-placement) | EnumSet&lt;NodeLabelPlacement&gt; | *not defined* | org.eclipse.elk.nodeLabels.placement
[Port Label Placement](org-eclipse-elk-portLabels-placement) | PortLabelPlacement | *not defined* | org.eclipse.elk.portLabels.placement
[Port Alignment](org-eclipse-elk-portAlignment-basic) | PortAlignment |  PortAlignment.JUSTIFIED | org.eclipse.elk.portAlignment.basic
[Port Alignment (North)](org-eclipse-elk-portAlignment-north) | PortAlignment | *not defined* | org.eclipse.elk.portAlignment.north
[Port Alignment (South)](org-eclipse-elk-portAlignment-south) | PortAlignment | *not defined* | org.eclipse.elk.portAlignment.south
[Port Alignment (West)](org-eclipse-elk-portAlignment-west) | PortAlignment | *not defined* | org.eclipse.elk.portAlignment.west
[Port Alignment (East)](org-eclipse-elk-portAlignment-east) | PortAlignment | *not defined* | org.eclipse.elk.portAlignment.east
[Edge Node Spacing Factor](org-eclipse-elk-layered-spacing-edgeNodeSpacingFactor) | float | *not defined* | org.eclipse.elk.layered.spacing.edgeNodeSpacingFactor
[Edge Spacing Factor](org-eclipse-elk-layered-spacing-edgeSpacingFactor) | float | *not defined* | org.eclipse.elk.layered.spacing.edgeSpacingFactor
[Add Unnecessary Bendpoints](org-eclipse-elk-layered-unnecessaryBendpoints) | boolean | *not defined* | org.eclipse.elk.layered.unnecessaryBendpoints
[Node Layering Strategy](org-eclipse-elk-layered-layering-strategy) | LayeringStrategy | *not defined* | org.eclipse.elk.layered.layering.strategy
[Node Promotion Strategy](org-eclipse-elk-layered-layering-nodePromotion-strategy) | NodePromotionStrategy | *not defined* | org.eclipse.elk.layered.layering.nodePromotion.strategy
[Thoroughness](org-eclipse-elk-layered-thoroughness) | int | *not defined* | org.eclipse.elk.layered.thoroughness
[Layer Constraint](org-eclipse-elk-layered-layering-layerConstraint) | LayerConstraint | *not defined* | org.eclipse.elk.layered.layering.layerConstraint
[Cycle Breaking Strategy](org-eclipse-elk-layered-cycleBreaking-strategy) | CycleBreakingStrategy | *not defined* | org.eclipse.elk.layered.cycleBreaking.strategy
[Crossing Minimization Strategy](org-eclipse-elk-layered-crossingMinimization-strategy) | CrossingMinimizationStrategy | *not defined* | org.eclipse.elk.layered.crossingMinimization.strategy
[Greedy Switch Crossing Minimization](org-eclipse-elk-layered-crossingMinimization-greedySwitch) | GreedySwitchType | *not defined* | org.eclipse.elk.layered.crossingMinimization.greedySwitch
[Semi-Interactive Crossing Minimization](org-eclipse-elk-layered-crossingMinimization-semiInteractive) | boolean | *not defined* | org.eclipse.elk.layered.crossingMinimization.semiInteractive
[Merge Edges](org-eclipse-elk-layered-mergeEdges) | boolean | *not defined* | org.eclipse.elk.layered.mergeEdges
[Merge Hierarchy-Crossing Edges](org-eclipse-elk-layered-mergeHierarchyEdges) | boolean | *not defined* | org.eclipse.elk.layered.mergeHierarchyEdges
[Interactive Reference Point](org-eclipse-elk-layered-interactiveReferencePoint) | InteractiveReferencePoint | *not defined* | org.eclipse.elk.layered.interactiveReferencePoint
[Node Placement Strategy](org-eclipse-elk-layered-nodePlacement-strategy) | NodePlacementStrategy | *not defined* | org.eclipse.elk.layered.nodePlacement.strategy
[Fixed Alignment](org-eclipse-elk-layered-nodePlacement-bk-fixedAlignment) | FixedAlignment | *not defined* | org.eclipse.elk.layered.nodePlacement.bk.fixedAlignment
[Edge Label Side Selection](org-eclipse-elk-layered-edgeLabelSideSelection) | EdgeLabelSideSelection | *not defined* | org.eclipse.elk.layered.edgeLabelSideSelection
[Feedback Edges](org-eclipse-elk-layered-feedbackEdges) | boolean | *not defined* | org.eclipse.elk.layered.feedbackEdges
[In-layer Spacing Factor](org-eclipse-elk-layered-spacing-inLayerSpacingFactor) | float | *not defined* | org.eclipse.elk.layered.spacing.inLayerSpacingFactor
[Wide Nodes on Multiple Layers](org-eclipse-elk-layered-layering-wideNodesOnMultipleLayers) | WideNodesStrategy | *not defined* | org.eclipse.elk.layered.layering.wideNodesOnMultipleLayers
[Linear Segments Deflection Dampening](org-eclipse-elk-layered-nodePlacement-linearSegments-deflectionDampening) | float | *not defined* | org.eclipse.elk.layered.nodePlacement.linearSegments.deflectionDampening
[Spline Self-Loop Placement](org-eclipse-elk-layered-edgeRouting-selfLoopPlacement) | SelfLoopPlacement | *not defined* | org.eclipse.elk.layered.edgeRouting.selfLoopPlacement
[Content Alignment](org-eclipse-elk-layered-contentAlignment) | EnumSet&lt;ContentAlignment&gt; | *not defined* | org.eclipse.elk.layered.contentAlignment
[Edge Straightening](org-eclipse-elk-layered-nodePlacement-bk-edgeStraightening) | EdgeStraighteningStrategy | *not defined* | org.eclipse.elk.layered.nodePlacement.bk.edgeStraightening
[Post Compaction Strategy](org-eclipse-elk-layered-compaction-postCompaction-strategy) | GraphCompactionStrategy | *not defined* | org.eclipse.elk.layered.compaction.postCompaction.strategy
[Post Compaction Constraint Calculation](org-eclipse-elk-layered-compaction-postCompaction-constraints) | ConstraintCalculationStrategy | *not defined* | org.eclipse.elk.layered.compaction.postCompaction.constraints
[Connected Components Compaction](org-eclipse-elk-layered-compaction-connectedComponents) | boolean | *not defined* | org.eclipse.elk.layered.compaction.connectedComponents
[High Degree Node Treatment](org-eclipse-elk-layered-highDegreeNodes-treatment) | boolean | *not defined* | org.eclipse.elk.layered.highDegreeNodes.treatment
[High Degree Node Threshold](org-eclipse-elk-layered-highDegreeNodes-threshold) | int | *not defined* | org.eclipse.elk.layered.highDegreeNodes.threshold
[High Degree Node Maximum Tree Height](org-eclipse-elk-layered-highDegreeNodes-treeHeight) | int | *not defined* | org.eclipse.elk.layered.highDegreeNodes.treeHeight
[Node Size Minimum](org-eclipse-elk-nodeSize-minimum) | KVector | *not defined* | org.eclipse.elk.nodeSize.minimum
[Minimum Width](org-eclipse-elk-nodeSize-minWidth) | float | *not defined* | org.eclipse.elk.nodeSize.minWidth
[Minimum Height](org-eclipse-elk-nodeSize-minHeight) | float | *not defined* | org.eclipse.elk.nodeSize.minHeight
[Junction Points](org-eclipse-elk-junctionPoints) | KVectorChain | *not defined* | org.eclipse.elk.junctionPoints
[Edge Thickness](org-eclipse-elk-edge-thickness) | float | *not defined* | org.eclipse.elk.edge.thickness
[Edge Label Placement](org-eclipse-elk-edgeLabels-placement) | EdgeLabelPlacement | *not defined* | org.eclipse.elk.edgeLabels.placement
[Port Index](org-eclipse-elk-port-index) | int | *not defined* | org.eclipse.elk.port.index
[Comment Box](org-eclipse-elk-commentBox) | boolean | *not defined* | org.eclipse.elk.commentBox
[Hypernode](org-eclipse-elk-hypernode) | boolean | *not defined* | org.eclipse.elk.hypernode
[Port Anchor Offset](org-eclipse-elk-port-anchor) | KVector | *not defined* | org.eclipse.elk.port.anchor
[Layout Partitioning](org-eclipse-elk-partitioning-activate) | Boolean | *not defined* | org.eclipse.elk.partitioning.activate
[Layout Partition](org-eclipse-elk-partitioning-partition) | Integer | *not defined* | org.eclipse.elk.partitioning.partition
[Distribute Nodes (Deprecated)](org-eclipse-elk-layered-layering-distributeNodes) | boolean | *not defined* | org.eclipse.elk.layered.layering.distributeNodes
[Upper Bound On Width [MinWidth Layerer]](org-eclipse-elk-layered-layering-minWidth-upperBoundOnWidth) | int | *not defined* | org.eclipse.elk.layered.layering.minWidth.upperBoundOnWidth
[Upper Layer Estimation Scaling Factor [MinWidth Layerer]](org-eclipse-elk-layered-layering-minWidth-upperLayerEstimationScalingFactor) | int | *not defined* | org.eclipse.elk.layered.layering.minWidth.upperLayerEstimationScalingFactor
[Sausage Folding](org-eclipse-elk-layered-sausageFolding) | boolean | *not defined* | org.eclipse.elk.layered.sausageFolding
[Position](org-eclipse-elk-position) | KVector | *not defined* | org.eclipse.elk.position
[North or South Port](org-eclipse-elk-layered-northOrSouthPort) | boolean | *not defined* | org.eclipse.elk.layered.northOrSouthPort
[Max Node Promotion Iterations](org-eclipse-elk-layered-layering-nodePromotion-maxIterations) | int | *not defined* | org.eclipse.elk.layered.layering.nodePromotion.maxIterations
[Edge Label Placement Strategy](org-eclipse-elk-layered-edgeCenterLabelPlacementStrategy) | EdgeLabelPlacementStrategy | *not defined* | org.eclipse.elk.layered.edgeCenterLabelPlacementStrategy
[Margins](org-eclipse-elk-margins) | Margins | *not defined* | org.eclipse.elk.margins
[Sloppy Spline Routing](org-eclipse-elk-layered-edgeRouting-sloppySplineRouting) | boolean | *not defined* | org.eclipse.elk.layered.edgeRouting.sloppySplineRouting
[Sloppy Spline Layer Spacing Factor](org-eclipse-elk-layered-edgeRouting-sloppySplineLayerSpacing) | float | *not defined* | org.eclipse.elk.layered.edgeRouting.sloppySplineLayerSpacing
[Layer Bound](org-eclipse-elk-layered-layering-coffmanGraham-layerBound) | int | *not defined* | org.eclipse.elk.layered.layering.coffmanGraham.layerBound

