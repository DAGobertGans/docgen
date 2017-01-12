---
layout: page
title: Activate Inside Self Loops
type: option
---
advanced

**Identifier:** org.eclipse.elk.insideSelfLoops.activate
**Meta Data Provider:** core.options.CoreOptions
**Type:** boolean
**Default Value:**  false  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** nodes

### Description
Whether this node allows to route self loops inside of it instead of around it. If set to true, this will make the node a compound node if it isn't already, and will require the layout algorithm to support compound nodes with hierarchical ports.

**Legacy Id:** de.cau.cs.kieler.selfLoopInside
**Containing Groups:** [insideSelfLoops](org-eclipse-elk-insideSelfLoops)

