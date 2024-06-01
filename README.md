# Shape Recognition and Clustering
A mesh clustering tool for Rhino3D. It can filter out similar 3d meshes from mesh pools. The tool is sensitive to minute changes in shapes of meshes. So even meshes with similar face counts but varied topologies can be differentiated successfully.

## Toolkit Purpose
The 3d shape recognition toolkit exposes the following new functionalities inside Rhino3D as commands:
1. Select similar mesh geometries.
2. Automated Clustering of mesh geometries.

## Use cases
1. **3D Geometry Clustering**: The tool allows for generation of 3d shape based estimates.
2. **Relevance in Architecture, Engineering and Construction**: Imagine a complex geometry facade with thousands of different mesh families spread across. The tool can automatically cluster and count unique shapes, and provide family clustering estimates. This information is exceptially useful in cost analysis and value engineering phases of building facades. An interesting exemplary project which demostrates the need for such a 3d analysis tool is this skyscraper from Zaha Hadid Architects in Melbourne, Australia. [Mandarin Oriental, Melbourne – Zaha Hadid Architects](https://www.zaha-hadid.com/interior_design/600-collins-street-melbourne/)

4. **Relevance in Archeology Research**: This can be an useful tool in finding similar shaped scanned artifacts in digital archives, and can be used by Archeologists who are interested in differentiating 3d artifacts based on minute details, and subtle variation of those details. Eg. the rim of the base of a ceramic cup/ the handles of kettles can vary across artifacts from different historic periods. All these are relevant important details, and this tool can help capture them.

## Documentation
### i. Mesh Picker from Mesh Pool
<p align="center" width="100%">
<img src="https://github.com/gasingh/shapeRecognition/blob/main/240530_meshSimilarity_pickFromMeshPool.gif" width="600" /> <br>
  The GIF illustrates the shape selection functionality.
</p>

### ii. Automated Shape Clusters
(WIP) <br>
The GIF illustrates automated generation of shape clusters from an unlabelled collection of objects.

### iii. Difference Volume Generation across similar looking meshes
(WIP) <br>
The GIF illustrates the generation of shape volumes for finding out shape differences.

___

