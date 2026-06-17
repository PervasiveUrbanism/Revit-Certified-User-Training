# Session 07: 2D Drafting and Detailing

## Goal

Create view-specific 2D details and understand when to use drafting tools rather than model elements.

## Prerequisites

- Basic annotation skills
- Familiarity with plans, sections, and view scales

## Key Concepts

- Drafting views
- Detail lines
- Line styles
- Line weights
- Filled regions
- Masking regions
- Detail components
- Insulation
- CAD links and imports

## Demonstration

Introduce drafting views as independent 2D views used for details that are not directly modelled. Explain scale management, referencing drafting views, and office detail library workflows.

Demonstrate detail lines, filled regions, masking regions, detail components, and insulation. Discuss safe CAD linking workflows and why exploding imported CAD can damage model performance.

## 2D Detail Component Families

Detail components are 2D annotation families used in drafting views and detail views. They are useful for repeated detail items such as people, fixings, brackets, insulation symbols, or standard construction components that do not need to be modelled in 3D.

To introduce the workflow, create a simple detail component family from a DWG reference:

- Start from a detail component family template.
- Import or link the DWG as a tracing reference.
- Draw clean Revit linework over the useful geometry.
- Add filled regions or masking regions where needed.
- Add a yes/no visibility parameter to control an optional part of the component.
- Load the detail component into the project and place it in a drafting view.

The important lesson is that office detail libraries should be made from clean Revit annotation elements where possible. Imported CAD can be useful as a starting point, but it should not become uncontrolled linework scattered through the project.

## Linking a Facade Detail

When using an external facade detail, prefer linking the CAD file into a controlled drafting view rather than importing and exploding it. A linked file can be reloaded, managed, and removed more safely. If the detail needs to become office-standard Revit content, trace or rebuild the necessary parts using Revit detail lines, filled regions, masking regions, and detail components.

## Exercise

1. Create a drafting view.
2. Set the view scale.
3. Draw a simple wall section detail with detail lines.
4. Add filled regions and masking regions.
5. Place detail components and insulation.
6. Add annotations and dimensions.
7. Link a facade DWG into a drafting view and review the link settings.
8. Create a simple 2D detail component family using a DWG as reference geometry.
9. Add a yes/no visibility parameter to an optional part of the detail component.
10. Load the detail component into the project and place it in the drafting view.
11. Place the drafting view on a detail sheet.

## Checklist

- [ ] I can create a drafting view.
- [ ] I understand detail lines versus model lines.
- [ ] I can use filled and masking regions.
- [ ] I can place detail components.
- [ ] I can create a simple 2D detail component family.
- [ ] I can add a basic visibility parameter to a detail component.
- [ ] I can link a CAD detail into a controlled drafting view.
- [ ] I can add insulation detail annotation.
- [ ] I understand the risks of importing and exploding CAD.

## Homework

- Recreate a simple construction detail from a PDF or CAD reference.

## Revit Help Links

- [Drafting views](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-F4D8EDE8-800D-4760-855B-39F00D069113)
- [Detail lines](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-A3EE5845-235D-4764-BF6D-3BA89C5C3686)
- [Detail components](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-9A2E4553-F3D8-4D83-90BA-9FC5166F59C1)
- [Filled and masking regions](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-183D9B1E-6554-4C19-9EA9-B32C8D2A5C9D)
- [Import or link CAD files](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-DEC9135F-75C1-4ACD-B34D-10CBBAD39F4C)
- [Family parameters](https://help.autodesk.com/view/RVT/2026/ENU/?guid=GUID-1F5D1A43-9199-4571-A9EB-0D4B4159C62B)
