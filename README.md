# MixedGroup

A *MixedGroup* is an ordered set (implemented as an Array) that holds two kinds of elements:

1. Element (*MixedGroup* is generic over *Element*)
2. Subgroup (Another child *MixedGroup*, generic over the same *Element* type)

*MixedGroupBuilder* is a Result Builder that builds a *MixedGroup* via a DSL much like *SwiftUI*.

##

MixedGroup back the data sets described in the Swift libraries *Piddy* (a Podcast directory), *Collegiate* (a University directory), and *Wavy* (a radio station directory). You might find use for it in another directory/database project.
