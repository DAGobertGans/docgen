---
layout: page
title: Port Side
type: option
---
## Port Side

----|----
**Type:** | programmatic
**Identifier:** | org.eclipse.elk.port.side
**Meta Data Provider:** | core.options.CoreOptions
**Value Type:** | `org.eclipse.elk.core.options.PortSide` (Enum)
**Possible Values:** | `EAST`, `NORTH`, `SIDES_EAST`, `SIDES_EAST_SOUTH`, `SIDES_EAST_SOUTH_WEST`, `SIDES_EAST_WEST`, `SIDES_NONE`, `SIDES_NORTH`, `SIDES_NORTH_EAST`, `SIDES_NORTH_EAST_SOUTH`, `SIDES_NORTH_EAST_SOUTH_WEST`, `SIDES_NORTH_EAST_WEST`, `SIDES_NORTH_SOUTH`, `SIDES_NORTH_SOUTH_WEST`, `SIDES_NORTH_WEST`, `SIDES_SOUTH`, `SIDES_SOUTH_WEST`, `SIDES_WEST`, `SOUTH`, `UNDEFINED`, `WEST`
**Default Value:** | `PortSide.UNDEFINED` (as defined in org.eclipse.elk)
**Applies To:** | ports
**Legacy Id:** | de.cau.cs.kieler.portSide
**Containing Groups:** | [port](org-eclipse-elk-port)


### Description
The side of a node on which a port is situated. This option must be set if 'Port Constraints' is set to FIXED_SIDE or FIXED_ORDER and no specific positions are given for the ports.

