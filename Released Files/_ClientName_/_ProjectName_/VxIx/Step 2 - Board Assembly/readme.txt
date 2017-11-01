If you use variants, create separate subdirectories for each variant.

Place following files here (or into the variant subdirectories):

- Mechanical Drawing (Board dimensions, holes position, ..)
- TOP and BOTTOM Assembly Drawing (Component position with Reference Designator)
- TOP and BOTTOM VIEW (shows board outline, assembly layer, TOP + BOTTOM layers)
- Bill of Materials (grouped by component type)
- Component reference BOM (each component on one line: Designator, Description, Manufacturer 1,
  Manufacturer, Part Number 1, Package / Case, Supplier 1, Supplier Part Number 1)
- Component reference BOM (as above) grouped by component type. Do not forget to increase width of rows where are hidden designators (select all the rows and double click on the left side bar on any row number).
- Pick and Place
- TOP and BOTTOM Layer + TOP and BOTTOM Paste Gerber Files (for stencil - if panel is done in a PCB house, ask them later for the top/bottom layers and paste for the panel)
- PDF 3D Model

- package file containing additional information without specified variant. This is useful when a custom variant will be assembled. This zip files should contain:
	- Component reference BOM for all components (each component on one line: Designator, Description, Manufacturer 1,
  Manufacturer, Part Number 1, Package / Case, Supplier 1, Supplier Part Number 1)
	- Pick and Place for all components



