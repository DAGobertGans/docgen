---
layout: page
title: Hierarchy Handling
type: option
---
## Hierarchy Handling

----|----
**Type:** | advanced
**Identifier:** | org.eclipse.elk.hierarchyHandling
**Meta Data Provider:** | core.options.CoreOptions
**Value Type:** | `org.eclipse.elk.core.options.HierarchyHandling` (Enum)
**Possible Values:** | `INCLUDE_CHILDREN`, `INHERIT`, `SEPARATE_CHILDREN`
**Default Value:** | `HierarchyHandling.INHERIT` (as defined in org.eclipse.elk)
**Applies To:** | parents, nodes
**Legacy Id:** | de.cau.cs.kieler.hierarchyHandling


### Description
Determines whether the descendants should be layouted separately or together with their parents. If the root node is set to inherit (or not set at all), the option is assumed as SEPARATE_CHILDREN.

