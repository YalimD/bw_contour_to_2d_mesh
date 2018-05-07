# ContourToMesh
## Generates a mesh from a binary image using OpenCV contours and Triangle library.

Requires: (On Python 3.6)
* Triangle
* Shapely
* Openmesh

| OpenCV Input  | Blender Result (.obj) |
| ------------- | --------------------- |
|![inputImage](test_images/a.png "Input Image in OpenCV")|![blenderResult](obj_files/a_result.png "Output .obj Mesh in Blender")|
|![inputImage](test_images/concave.png "Input Image in OpenCV")|![blenderResult](obj_files/concave_result.png "Output .obj Mesh in Blender")|
|![inputImage](test_images/multiple.png "Input Image in OpenCV")|![blenderResult](obj_files/multiple_result.png "Output .obj Mesh in Blender")|
|![inputImage](test_images/worst.png "Input Image in OpenCV")|![blenderResult](obj_files/worst_result.png "Output .obj Mesh in Blender")|
|![inputImage](test_images/real_area.png "Input Image in OpenCV")|![blenderResult](obj_files/real_area_result.png "Output .obj Mesh in Blender")|

> Note that the last image has been dilated/eroded in order to make the mesh more connected.
