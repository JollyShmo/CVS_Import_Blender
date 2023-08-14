# CSV Mesh Importer Blender Addon

This Blender addon allows you to import points from a CSV file and create a mesh with connected edges. It's particularly useful for visualizing 3D point data captured using tools like 'RenderDoc'. 

## Features
- Import vertex points from a CSV file.
- Create a mesh with connected edges based on the imported points.
- Automatically remove duplicate vertices.
- Provides a simple way to visualize point data in Blender's 3D view.

## Usage
1. Download the `csv_mesh_importer.py` script.
2. In Blender, open the 'Edit' menu, select 'Preferences', and navigate to the 'Add-ons' section.
3. Click the 'Install' button and choose the `csv_mesh_importer.py` script.
4. Enable the addon by checking the corresponding checkbox.
5. Now, you can import CSV files containing vertex data by going to 'File > Import' and selecting 'CSV Mesh (.csv)'.

## Credits
- Author: Jolly Joe
- Version: 1.0
- Blender Compatibility: 2.93 or later
- Category: Import-Export

Please note that this addon creates a mesh with connected edges based on the imported points. It's important to review the results and refine the mesh as needed after import. Some unwanted edges might be generated, and further adjustments may be required for complex data.

For more information, visit the [Blender Addon Documentation](https://www.blender.org/manual/scripting/introduction.html) and [RenderDoc](https://renderdoc.org/) websites.
