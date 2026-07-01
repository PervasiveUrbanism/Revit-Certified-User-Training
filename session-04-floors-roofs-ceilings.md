# Session 04: Floors, Roofs and Ceilings

## Goal

Create horizontal building elements and understand Revit's sketch-based workflows.

## Prerequisites

- Session 03 completed
- A simple wall layout
- Basic edit mode awareness

## Key Concepts

- Sketch mode
- Floor boundaries
- Pick Walls workflow
- Floor type layers
- Roof by footprint
- Slope-defining edges
- Ceiling plans
- Reflected ceiling plans
- Stairs, ramps, and railings
- Sketch draw tools and chain selection

## Demonstration

Introduce floors as sketch-based system families. Show manual sketching, Pick Walls, boundary cleanup, and basic floor type layers.

Then demonstrate Roof by Footprint, overhang settings, slope-defining edges, and attaching walls to roof geometry. Finish by opening a reflected ceiling plan and creating ceilings. Add a focused exam demonstration of sketch draw tools: line, rectangle, start-end-radius arc, pick lines, pick walls, chain selection, Extend into Wall, and Escape, Shift, Alt, Tab, and PageUp during sketch workflows.

Close the session with a short introduction to straight stairs, ramps, and railings because these are part of the ACU modelling domain.

## Roof Types and Edge Conditions

Roof types work like other system family types: duplicate an existing type, rename it clearly, then edit the type properties and structure. For the training model, learners should understand the difference between changing a roof instance, changing a roof type, and changing the sketch that defines the roof footprint.

Roof edges often need additional elements. Eaves describe the projecting lower edge of a roof. Fascia can be added to exposed roof edges. Soffits can close the underside of an overhang. Gutters can be placed along roof edges to represent rainwater collection.

Dormers are a useful example of how roof modelling becomes more complex. Learners do not need to master dormers in this session, but they should recognise that dormers combine roof geometry, openings, wall conditions, and careful sketch control.

## Floor Edges and Profile Families

Floor slab edges are hosted profiles that can be added to floor edges. They are useful for slab thickening, edge beams, or shaped perimeter conditions. In this course, introduce the idea briefly so learners know the tool exists, but keep the main exercise focused on floor boundaries and type layers.

Profile families control the shape used by tools such as wall sweeps, reveals, fascias, gutters, railings, and slab edges. The detailed creation of profile families belongs later, alongside family editing and custom content. For now, learners only need to understand that these edge tools often rely on a separate profile shape.

## Exercise

1. Create a floor using Pick Walls.
2. Edit the floor boundary.
3. Review floor type layers.
4. Create a roof by footprint.
5. Set roof overhangs and slope edges.
6. Duplicate a roof type and review its structure.
7. Add or discuss eaves, fascia, soffits, and gutters.
8. Attach walls to the roof where appropriate.
9. Open a reflected ceiling plan and create ceilings.
10. Use line, rectangle, arc, pick lines, pick walls, and chain selection in sketch mode.
11. Place a straight stair with a run and landing.
12. Sketch a simple ramp and add or edit a railing path.

## Checklist

- [ ] I can enter and finish sketch mode.
- [ ] I can create floors from wall boundaries.
- [ ] I can create a simple roof by footprint.
- [ ] I can duplicate a roof type and review roof structure.
- [ ] I understand slope-defining edges.
- [ ] I can identify eaves, fascia, soffits, gutters, and slab edges.
- [ ] I can create a reflected ceiling plan.
- [ ] I can use the ACU sketch draw tools.
- [ ] I can place basic stairs, ramps, and railings.

## Homework

- Model a simple house roof.
- Create a floor and ceiling for a small room layout.

## Revit Help Links


- [Floors](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-8099AC26-F02D-4C9A-9209-AAD95A10D119)
- [Roofs](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-FF37F25A-D805-4F2E-B9FC-4372CAFDF4FC)
- [Ceilings](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-DA92880A-0A23-4EB4-A20B-CC70966B7C36)
- [Stairs](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-B1B305DF-8DBE-44A7-A7C6-16B70A3B580E)
- [Railings](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-34DEB2F6-E66E-4801-8138-958DDB4D2A5A)
- [Eaves](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-0557B197-B1B1-4788-8C8A-69B50047647D)
- [Fascia](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-CAD0E3C1-1B3C-4B5C-B399-A62AE3A0F360)
- [Soffits](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-390A6DAA-8C17-4E6C-8901-109A34ADEFB1)
- [Gutters](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-7DE5AA79-94A8-4912-A7AF-444F64FF5158)
- [Dormer video](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-74EF6372-19B6-4D71-AC66-6CE8BE7D29DB)
- [Floor slab edge](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-D54C7E2D-CCCE-4744-9507-0BFCEB6270B5)
- [Profile families](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-62C3B203-3B8E-4798-8CF0-CC166F9BEBFA)
- [Floor tutorial](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-02936CA2-FE9E-4625-A2A6-A45324937847)
- [Roof tutorial](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-5924644F-C73E-4B76-897D-B181EE9F1B16)
