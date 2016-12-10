---
layout: page
title: ELK Layered
type: algorithm
---
org.eclipse.elk.layered

Layer-based algorithm provided by the Eclipse Layout Kernel. Arranges as many edges as possible into one direction by placing nodes into subsequent layers. This implementation supports different routing styles (straight, orthogonal, splines); if orthogonal routing is selected, arbitrary port constraints are respected, thus enabling the layout of block diagrams such as actor-oriented models or circuit schematics. Furthermore, full layout of compound graphs with cross-hierarchy edges is supported when the respective option is activated on the top level.

## Preview
![](images/layered.png)

## Meta Data Provider
properties.LayeredMetaDataProvider

## Supported Graph Features
SELF_LOOPS
INSIDE_SELF_LOOPS
MULTI_EDGES
EDGE_LABELS
PORTS
COMPOUND
CLUSTERS

## Category
### Layered
The layer-based method was introduced by Sugiyama, Tagawa and Toda in 1981. It emphasizes the direction of edges by pointing as many edges as possible into the same direction. The nodes are arranged in layers, which are sometimes called "hierarchies", and then reordered such that the number of edge crossings is minimized. Afterwards, concrete coordinates are computed for the nodes and edge bend points.

## Supported Options

Option | regular default | algorithm default
----|----|----
[Node Spacing](org-eclipse-elk-spacing-node) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@43b5e2a (value: 20) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@6e0b476d (value: 20)
[Border Spacing](org-eclipse-elk-spacing-border) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@20418f1d (value: 12) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@595848b9 (value: 12)
[Port Spacing](org-eclipse-elk-spacing-port) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@52f50fd4 (value: 10) | 
[Label Spacing](org-eclipse-elk-spacing-label) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@5cd4cfb8 (value: 0) | 
[Priority](org-eclipse-elk-priority) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1bbc6a11 (value: 0)
[Edge Routing](org-eclipse-elk-edgeRouting) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.ORTHOGONAL
[Port Border Offset](org-eclipse-elk-port-borderOffset) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@3f923b9a (value: 0)
[Randomization Seed](org-eclipse-elk-randomSeed) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@48df8fc4 (value: 1)
[Aspect Ratio](org-eclipse-elk-aspectRatio) |  | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@11c571f4 (value: 1.6f)
[No Layout](org-eclipse-elk-noLayout) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@7aa33f2b (isTrue: false) | 
[Port Constraints](org-eclipse-elk-portConstraints) | <XFeatureCallImplCustom>.UNDEFINED | 
[Port Side](org-eclipse-elk-port-side) | <XFeatureCallImplCustom>.UNDEFINED | 
[Debug Mode](org-eclipse-elk-debugMode) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@e926506 (isTrue: false) | 
[Alignment](org-eclipse-elk-alignment) | <XFeatureCallImplCustom>.AUTOMATIC | 
[Layout Hierarchy](org-eclipse-elk-layoutHierarchy) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@74abd464 (isTrue: false) | 
[Hierarchy Handling](org-eclipse-elk-hierarchyHandling) | <XFeatureCallImplCustom>.INHERIT | 
[Separate Connected Components](org-eclipse-elk-separateConnectedComponents) |  | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@a2b5dce (isTrue: true)
[Activate Inside Self Loops](org-eclipse-elk-insideSelfLoops-activate) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@2c141136 (isTrue: false) | 
[Inside Self Loop](org-eclipse-elk-insideSelfLoops-yo) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@2b77afea (isTrue: false) | 
[Node Size Constraints](org-eclipse-elk-nodeSize-constraints) | <XFeatureCallImplCustom>.noneOf(<XFeatureCallImplCustom>) | 
[Node Size Options](org-eclipse-elk-nodeSize-options) | <XFeatureCallImplCustom>.of(<XMemberFeatureCallImplCustom>,<XMemberFeatureCallImplCustom>) | 
[Direction](org-eclipse-elk-direction) | <XFeatureCallImplCustom>.UNDEFINED | <XFeatureCallImplCustom>.UNDEFINED
[Node Label Placement](org-eclipse-elk-nodeLabels-placement) | <XFeatureCallImplCustom>.fixed | 
[Port Label Placement](org-eclipse-elk-portLabels-placement) | <XFeatureCallImplCustom>.OUTSIDE | 
[Port Alignment](org-eclipse-elk-portAlignment-basic) | <XFeatureCallImplCustom>.JUSTIFIED | <XFeatureCallImplCustom>.JUSTIFIED
[Port Alignment (North)](org-eclipse-elk-portAlignment-north) | <XFeatureCallImplCustom>.UNDEFINED | 
[Port Alignment (South)](org-eclipse-elk-portAlignment-south) | <XFeatureCallImplCustom>.UNDEFINED | 
[Port Alignment (West)](org-eclipse-elk-portAlignment-west) | <XFeatureCallImplCustom>.UNDEFINED | 
[Port Alignment (East)](org-eclipse-elk-portAlignment-east) | <XFeatureCallImplCustom>.UNDEFINED | 
[Edge Node Spacing Factor](org-eclipse-elk-layered-spacing-edgeNodeSpacingFactor) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@2b0b487f (value: 0.5f) | 
[Edge Spacing Factor](org-eclipse-elk-layered-spacing-edgeSpacingFactor) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@4cbae0c6 (value: 0.5f) | 
[Add Unnecessary Bendpoints](org-eclipse-elk-layered-unnecessaryBendpoints) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@67af3bee (isTrue: false) | 
[Node Layering Strategy](org-eclipse-elk-layered-layering-strategy) | <XFeatureCallImplCustom>.NETWORK_SIMPLEX | 
[Node Promotion Strategy](org-eclipse-elk-layered-layering-nodePromotion-strategy) | <XFeatureCallImplCustom>.NONE | 
[Thoroughness](org-eclipse-elk-layered-thoroughness) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1c935484 (value: 7) | 
[Layer Constraint](org-eclipse-elk-layered-layering-layerConstraint) | <XFeatureCallImplCustom>.NONE | 
[Cycle Breaking Strategy](org-eclipse-elk-layered-cycleBreaking-strategy) | <XFeatureCallImplCustom>.GREEDY | 
[Crossing Minimization Strategy](org-eclipse-elk-layered-crossingMinimization-strategy) | <XFeatureCallImplCustom>.LAYER_SWEEP | 
[Greedy Switch Crossing Minimization](org-eclipse-elk-layered-crossingMinimization-greedySwitch) | <XFeatureCallImplCustom>.TWO_SIDED | 
[Semi-Interactive Crossing Minimization](org-eclipse-elk-layered-crossingMinimization-semiInteractive) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@560044b8 (isTrue: false) | 
[Merge Edges](org-eclipse-elk-layered-mergeEdges) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@22b84bf7 (isTrue: false) | 
[Merge Hierarchy-Crossing Edges](org-eclipse-elk-layered-mergeHierarchyEdges) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@57a7efe2 (isTrue: true) | 
[Interactive Reference Point](org-eclipse-elk-layered-interactiveReferencePoint) | <XFeatureCallImplCustom>.CENTER | 
[Node Placement Strategy](org-eclipse-elk-layered-nodePlacement-strategy) | <XFeatureCallImplCustom>.BRANDES_KOEPF | 
[Fixed Alignment](org-eclipse-elk-layered-nodePlacement-bk-fixedAlignment) | <XFeatureCallImplCustom>.NONE | 
[Edge Label Side Selection](org-eclipse-elk-layered-edgeLabelSideSelection) | <XFeatureCallImplCustom>.ALWAYS_DOWN | 
[Feedback Edges](org-eclipse-elk-layered-feedbackEdges) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@182a9b43 (isTrue: false) | 
[In-layer Spacing Factor](org-eclipse-elk-layered-spacing-inLayerSpacingFactor) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@46a36a82 (value: 1) | 
[Wide Nodes on Multiple Layers](org-eclipse-elk-layered-layering-wideNodesOnMultipleLayers) | <XFeatureCallImplCustom>.OFF | 
[Linear Segments Deflection Dampening](org-eclipse-elk-layered-nodePlacement-linearSegments-deflectionDampening) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@42e159c4 (value: 0.3f) | 
[Spline Self-Loop Placement](org-eclipse-elk-layered-edgeRouting-selfLoopPlacement) | <XFeatureCallImplCustom>.NORTH_STACKED | 
[Content Alignment](org-eclipse-elk-layered-contentAlignment) | <XFeatureCallImplCustom>.noneOf(<XFeatureCallImplCustom>) | 
[Edge Straightening](org-eclipse-elk-layered-nodePlacement-bk-edgeStraightening) | <XFeatureCallImplCustom>.IMPROVE_STRAIGHTNESS | 
[Post Compaction Strategy](org-eclipse-elk-layered-compaction-postCompaction-strategy) | <XFeatureCallImplCustom>.NONE | 
[Post Compaction Constraint Calculation](org-eclipse-elk-layered-compaction-postCompaction-constraints) | <XFeatureCallImplCustom>.SCANLINE | 
[Connected Components Compaction](org-eclipse-elk-layered-compaction-connectedComponents) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@3baac456 (isTrue: false) | 
[High Degree Node Treatment](org-eclipse-elk-layered-highDegreeNodes-treatment) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@cfed2c3 (isTrue: false) | 
[High Degree Node Threshold](org-eclipse-elk-layered-highDegreeNodes-threshold) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@26293428 (value: 16) | 
[High Degree Node Maximum Tree Height](org-eclipse-elk-layered-highDegreeNodes-treeHeight) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@5cee868b (value: 5) | 
[Node Size Minimum](org-eclipse-elk-nodeSize-minimum) |  | 
[Minimum Width](org-eclipse-elk-nodeSize-minWidth) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@1e8e8f91 (value: 0) | 
[Minimum Height](org-eclipse-elk-nodeSize-minHeight) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@9ae2f10 (value: 0) | 
[Junction Points](org-eclipse-elk-junctionPoints) |  | 
[Edge Thickness](org-eclipse-elk-edge-thickness) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@7430ddec (value: 1) | 
[Edge Label Placement](org-eclipse-elk-edgeLabels-placement) | <XFeatureCallImplCustom>.UNDEFINED | 
[Port Index](org-eclipse-elk-port-index) |  | 
[Comment Box](org-eclipse-elk-commentBox) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@54771e03 (isTrue: false) | 
[Hypernode](org-eclipse-elk-hypernode) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@39ced18c (isTrue: false) | 
[Port Anchor Offset](org-eclipse-elk-port-anchor) |  | 
[Layout Partitioning](org-eclipse-elk-partitioning-activate) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@2b9c7ea3 (isTrue: false) | 
[Layout Partition](org-eclipse-elk-partitioning-partition) |  | 
[Distribute Nodes (Deprecated)](org-eclipse-elk-layered-layering-distributeNodes) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@76b63921 (isTrue: false) | 
[Upper Bound On Width [MinWidth Layerer]](org-eclipse-elk-layered-layering-minWidth-upperBoundOnWidth) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@6b5ae216 (value: 4) | 
[Upper Layer Estimation Scaling Factor [MinWidth Layerer]](org-eclipse-elk-layered-layering-minWidth-upperLayerEstimationScalingFactor) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@7466dc14 (value: 2) | 
[Sausage Folding](org-eclipse-elk-layered-sausageFolding) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@19c74168 (isTrue: false) | 
[Position](org-eclipse-elk-position) |  | 
[North or South Port](org-eclipse-elk-layered-northOrSouthPort) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@34d20e4b (isTrue: false) | 
[Max Node Promotion Iterations](org-eclipse-elk-layered-layering-nodePromotion-maxIterations) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@86fc853 (value: 0) | 
[Edge Label Placement Strategy](org-eclipse-elk-layered-edgeCenterLabelPlacementStrategy) | <XFeatureCallImplCustom>.CENTER | 
[Margins](org-eclipse-elk-margins) | org.eclipse.xtext.xbase.impl.XConstructorCallImplCustom@7fb3d1de (invalidFeatureIssueCode: null, validFeature: false, explicitConstructorCall: false, anonymousClassConstructorCall: false) | 
[Sloppy Spline Routing](org-eclipse-elk-layered-edgeRouting-sloppySplineRouting) | org.eclipse.xtext.xbase.impl.XBooleanLiteralImpl@2c821ee4 (isTrue: true) | 
[Sloppy Spline Layer Spacing Factor](org-eclipse-elk-layered-edgeRouting-sloppySplineLayerSpacing) | org.eclipse.xtext.xbase.impl.XNumberLiteralImpl@36cfa261 (value: 0.4f) | 
[Layer Bound](org-eclipse-elk-layered-layering-coffmanGraham-layerBound) | <XFeatureCallImplCustom>.MAX_VALUE | 

