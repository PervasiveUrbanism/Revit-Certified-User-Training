# Session 01: Getting Started With Revit

## Goal

Understand the Revit workspace, open a project, navigate views, and recognise the main tools used during a basic modelling session.

## Prerequisites

- Autodesk Revit installed
- Download the [Lesson 01 exercise file](assets/exercise-files/lesson-01.rvt)
- A sample project or Revit default template

## Key Concepts

- BIM vs CAD
- MacLeamy Curve
- Project Browser
- Properties Palette
- Ribbon tools
- View controls
- 3D navigation
- Selection and modification tools
- Basic digital literacy for opening, saving, and finding files

## BIM vs CAD

Introduce Revit as a coordinated BIM model rather than a set of disconnected CAD drawings. Show how plans, sections, elevations, schedules, and sheets all read from the same project model.

One of the most important ideas in Revit is that the project behaves like a central database. A wall is not just a line in plan; it is an object with height, type, material, fire rating, location, and relationships to levels, rooms, views, schedules, and sheets. When that object changes, every view that depends on it can update from the same underlying information.

For example, imagine Keyu is preparing facade visualisations. In a less coordinated workflow, she might export geometry from Revit, adjust it in Rhino, assign materials, and send it to D5 or another visualisation tool. If the facade geometry or material changes later, those changes may happen outside Revit. Martin, the technical coordinator, then needs to update drawings or schedules separately, and Richard, the facade coordinator, needs to check whether the facade information still matches. The team can quickly end up with several versions of the same building.

In a Revit-based BIM workflow, Keyu makes the relevant geometry and material changes in the live project model where possible. Plans, sections, elevations, schedules, and sheets can then read the updated information from the same place. If the model is linked into D5 or another visualisation workflow, the visualisation is based on current coordinated geometry, reducing the risk that material assignments or design changes are lost during export.

### MacLeamy Curve

The MacLeamy Curve is a useful way to explain why BIM changes the design process. It compares the ability to influence project outcomes, the cost of making changes, and where design effort usually happens.

![MacLeamy Curve showing effort, cost of change, traditional design process, and preferred design process](assets/macleamy-curve.jpg)

Source: [DDG Global, "MacLeamy Curve - How BIM affects the design process"](https://www.ddg.global/post/macleamy-curve-how-bim-affects-the-design-process).

The key lesson for Revit users is that BIM rewards earlier thinking. Coordinated models, shared information, and earlier collaboration help teams make important decisions while they are still relatively cheap and easy to change.

Then orient learners around the interface:

- Ribbon tabs and panels
- Quick Access Toolbar
- Properties Palette
- Project Browser
- View Control Bar
- Status Bar

## Exercise

1. Open Revit and create a new architectural project.
2. Discuss where Revit shifts effort compared with a traditional drawing-led workflow.
3. Find the Project Browser and Properties Palette.
4. Open a floor plan, elevation, section, and 3D view.
5. Practice zooming, panning, orbiting, and switching between views.
6. Select model elements using click, window selection, tab select, and filters.
7. Use move, copy, rotate, and temporary hide/isolate.
8. Try trim/extend, align, offset, mirror, split, array, scale, pin/unpin, and copy/paste aligned on prepared elements.
9. Save the project locally.

## Checklist

- [ ] I can create or open a Revit project.
- [ ] I can explain why BIM shifts design decisions earlier in the project.
- [ ] I can identify the main interface areas.
- [ ] I can switch between common view types.
- [ ] I can navigate a model in 2D and 3D.
- [ ] I can select and modify basic elements.
- [ ] I can use the core Modify tools listed in the ACU objectives.

## Homework

- Practice navigation shortcuts.
- Open and explore sample projects.
- Duplicate a view and rename it clearly.

## Revit Help Links


- [Revit user interface](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-7793667D-5657-4382-9BEC-F7CB6AC8F53E)
- [Project Browser](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-C8D3E5A6-02A5-43A9-AFFC-D49DD27398B1)
- [Navigate views](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-D6D06E2C-17F3-499B-B795-E2980C46BBF2)
- [Editing Elements](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-33CE9B38-CACD-47D6-936B-01776C4BC324)
