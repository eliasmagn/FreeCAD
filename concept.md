# Project Concept

FreeCAD is an extensible, open-source parametric CAD platform that combines a powerful geometric kernel with a Python-friendly automation layer. The application delivers feature-rich workbenches so users can move from sketching to 3D modelling, documentation, and manufacturing preparation inside a single environment.

## Sketcher editing vision

The Sketcher workbench focuses on precise 2D constraint-based workflows. Enhancements like the new "Split Edge at Point" capability ensure designers can refine complex sketches without breaking constraints by cutting a selected curve exactly where a reference point or vertex already exists. This keeps downstream operations stable while reducing the need for manual cleanup.

Maintaining design intent is essential when subdividing geometry, so the split workflow now carries angular orientation constraints forward onto the resulting line segments. Designers can split an angled edge and keep the original angle relationships intact, eliminating tedious rework after each refinement.
