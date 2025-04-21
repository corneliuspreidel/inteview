
# Task: Ground Plane Detection from CSV

In the context of digital twins, robotics, or model-based processing, detecting **dominant planes** (e.g. floors or ceilings) in a point cloud is often a first essential step. This plane becomes a reference for further segmentation, object extraction, or anchoring.

### Input

You are provided with a point cloud in CSV format:

```
data/point_cloud_factory.csv
```

*Approx. 20,000 rows with 3 columns:*

```
x, y, z
14.23, 10.35, 0.01
```

*Coordinates are in meters.*

This data contains a horizontal ground plane with some objects above it.

### Your Task

Create a script or notebook that:

1. **Loads** the CSV into a suitable data structure.
2. **Finds the dominant (horizontal) ground plane** from the point cloud data.
3. **Visually marks** the ground plane so it is clearly distinguishable from other points.
   * For example: different color, mesh surface, or separation in viewer.
4. At the end of the task, be prepared to:
   * **Explain your approach and thought process** ,
   * **Show and explain your code** , and
   * **Describe the tools and methods** you used (and why you chose them).

### Time Budget

**20 minutes total.**

Focus on an end-to-end working example, even if it's minimal. Clean structure and clear reasoning matter most.

### Notes

* You may use **any language, framework, or library** you’re comfortable with (e.g. Open3D, PCL, NumPy, SciPy, Plotly, Three.js, etc.).
* Internet access and package installation is allowed.
* Don’t worry about perfection — we care most about how you approach the problem and communicate your choices.
