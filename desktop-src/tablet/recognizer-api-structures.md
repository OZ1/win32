---
Description: This section describes the recognizer structures.
ms.assetid: 4c17391f-7af4-42ab-b77f-e3c39cadc0b6
title: Recognizer Structures
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Recognizer Structures

This section describes the recognizer structures.

## In This Section



| Structure                                                    | Description                                                                                                                                                   |
|--------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**CHARACTER\_RANGE**](/windows/desktop/api/rectypes/ns-rectypes-tagcharacter_range)                  | Specifies a range of Unicode points (characters).<br/>                                                                                                  |
| [**LATTICE\_METRICS**](/windows/desktop/api/rectypes/ns-rectypes-taglattice_metrics)                  | Describes the baseline and the midline height.<br/>                                                                                                     |
| [**LINE\_SEGMENT**](/windows/desktop/api/rectypes/ns-rectypes-tagline_segment)                        | Describes the start and end points of a line recognition segment, such as the baseline or midline.<br/>                                                 |
| [**PACKET\_DESCRIPTION**](/windows/desktop/api/tpcshrd/ns-tpcshrd-_packet_description)            | Describes the content of the packet for a particular tablet context.<br/>                                                                               |
| [**PACKET\_PROPERTY**](/windows/desktop/api/tpcshrd/ns-tpcshrd-_packet_property)                  | Describes a packet property that is reported by the tablet driver.<br/>                                                                                 |
| [**PROPERTY\_METRICS**](/windows/desktop/api/tpcshrd/ns-tpcshrd-_property_metrics)                | Defines the range and resolution of a packet property.<br/>                                                                                             |
| [**RECO\_ATTRS**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_attrs)                            | Retrieves the attributes of a recognizer or specifies which attributes to use when you search for an installed recognizer.<br/>                         |
| [**RECO\_GUIDE**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_guide)                            | Defines the boundaries of the ink to the recognizer.<br/>                                                                                               |
| [**RECO\_LATTICE**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_lattice)                        | Serves as the entry point into a lattice.<br/>                                                                                                          |
| [**RECO\_LATTICE\_COLUMN**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_lattice_column)         | Represents a column in the lattice.<br/>                                                                                                                |
| [**RECO\_LATTICE\_ELEMENT**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_lattice_element)       | Corresponds to one word or one East Asian character, typically; however, an element may also correspond to a gesture, a shape, or some other code.<br/> |
| [**RECO\_LATTICE\_PROPERTIES**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_lattice_properties) | Contains an array of pointers to property structures.<br/>                                                                                              |
| [**RECO\_LATTICE\_PROPERTY**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_lattice_property)     | Contains a property used in the lattice.<br/>                                                                                                           |
| [**RECO\_RANGE**](/windows/desktop/api/rectypes/ns-rectypes-tagreco_range)                            | Identifies a range of characters in the result string.<br/>                                                                                             |
| [**STROKE\_RANGE**](/windows/desktop/api/tpcshrd/ns-tpcshrd-tagstroke_range)                        | Specifies a range of strokes in the [**InkDisp**](inkdisp-class.md) object.<br/>                                                                       |



 

 

 



