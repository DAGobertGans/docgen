---
layout: page
title: Box Layout Mode
type: option
---

**Identifier:** org.eclipse.elk.box.packingMode
**Meta Data Provider:** core.options.CoreOptions
**Type:** org.eclipse.elk.core.util.BoxLayoutProvider$PackingMode
**Default Value:**  BoxLayoutProvider.PackingMode.SIMPLE  (not specific to an algorithm)
**Lower Bound:** *not defined*
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
Configures the packing mode used by the {@link BoxLayoutProvider}. If SIMPLE is not required (neither priorities are used nor the interactive mode), GROUP_DEC can improve the packing and decrease the area. GROUP_MIXED and GROUP_INC may, in very specific scenarios, work better.

**Containing Groups:** [box](org-eclipse-elk-box)

