---
layout: page
title: FR Temperature
type: option
---

**Identifier:** org.eclipse.elk.force.temperature
**Meta Data Provider:** properties.ForceMetaDataProvider
**Type:** double
**Default Value:**  0.001  (not specific to an algorithm)
**Lower Bound:**  ExclusiveBounds.greaterThan(0)
**Upper Bound:** *not defined*
**Applies To:** parents

### Description
The temperature is used as a scaling factor for particle displacements.

**Dependencies:** org.eclipse.elk.force.model

