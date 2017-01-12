---
layout: page
title: Port Index
type: option
---
programmatic

**Identifier:** org.eclipse.elk.port.index
**Meta Data Provider:** core.options.CoreOptions
**Type:** int
**Default Value:** *not defined*  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** ports

### Description
The index of a port in the fixed order around a node. The order is assumed as clockwise, starting with the leftmost port on the top side. This option must be set if 'Port Constraints' is set to FIXED_ORDER and no specific positions are given for the ports. Additionally, the option 'Port Side' must be defined in this case.

**Legacy Id:** de.cau.cs.kieler.portIndex
**Containing Groups:** [port](org-eclipse-elk-port)

