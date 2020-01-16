# ycb-objects-models-sim

Repository containing models of a subset of YCB objects. For each object there is:
  - textured mesh file (`.obj`)
  - URDF file that can be loaded in a simulator. So far, it has been tested only in pyBullet

Furthermore, there are three SDF files, each loading a group of objects according to a specific layout. The layouts reproduce the layouts of the [GRASPA-benchmark](https://github.com/robotology/GRASPA-benchmark).

The original textured meshes were taken from the official website of the YCB benchmarks ([here](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/)). Then, they have been repositioned in MeshLab to match the pose of the corresponding non-textured meshes.