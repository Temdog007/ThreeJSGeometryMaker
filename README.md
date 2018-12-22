# ThreeJSGeometryMaker
Tool to create geometries specifically for the ThreeJS framework. This tool will allow users to create BufferGeometry JSON code to be used in the [ThreeJS framework](https://github.com/mrdoob/three.js/). Users can place a series of vertices and edit their position, UV, and color. Users can also define triangles that make up the mesh.

## How to Use
### Adding vertices
- Use the mouse to place a vertex.
- Press the *Insert* key to add a vertex.

### Editing vertices
- Click on an existing vertex.
- Use the side bar to edit the vertex's position and UV coodrinates.

### Delete vertices
- Hold the *ctrl* key and click on an existing vertex while it is visible.

### Adding triangles
- Hold the *shift* key and select a vertex.
- After selecting 3 vertices, a triangle will be formed. (NOTE: the normal of the triangle will determined based on the order the vertices. This is important if the material of the mesh is not set the DoubleSide).

### Deleteing triangles
- Hold the *shift* key and select a triangle while it is visible.

### Show/Dispaly
- Press *F1* to toggle vertices
- Press *tilde* to toggle UV boxes
- Press *F2* to toggle image mapping
- Press *F4* to toggle triangles

### Screenshot
[](images/ThreeJS Geometry Maker screenshot.png)
