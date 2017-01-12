---
layout: page
title: Label Manager
type: option
---
programmatic

**Identifier:** org.eclipse.elk.labels.labelManager
**Meta Data Provider:** LabelManagementOptions
**Type:** org.eclipse.elk.core.labels.ILabelManager
**Default Value:** *not defined*  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents, labels

### Description
The label manager responsible for a given part of the graph. A label manager can either be attached to a compound node (in which case it is responsible for all labels inside) or to specific labels. The label manager can then be called by layout algorithms to modify labels that are too wide to try and shorten them to a given target width.


