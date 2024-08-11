A
# Curvetopia-Adobe

Welcome to **Curvetopia-Adobe**, a project dedicated to bringing order and beauty to the world of 2D curves! This repository is a journey into identifying, regularizing, and beautifying various types of curves in 2D Euclidean space, with a focus on closed curves, symmetry, and curve completion techniques.


## Objective
The mission of Curvetopia-Adobe is to develop a comprehensive process for identifying,regularizing, and beautifying curves, starting with simple shapes and progressing to more complex forms. The project is designed to work with curves represented by cubic Bézier curves and polylines, with outputs visualized in SVG format.

## Features

### Regularize Curves
Identify and categorize regular shapes from a given set of curves:
- **Straight Lines**: Detect straight lines within the curve data.
- **Circles and Ellipses**: Identify circular A where all points are equidistant from a center or ellipses with two focal points.
- **Rectangles and Rounded Rectangles**: Distinguish between sharp-edged and rounded rectangles.
- **Regular Polygons**: Detect polygons with equal sides and angles.
- **Star Shapes**: Identify star-shaped curves with a central point and radial arms.

### Exploring Symmetry in Curves
Focus on closed shapes and identify various types of symmetry, including reflection symmetry. The project aims to transform curves into sets of points and fit Bézier curves to points that exhibit symmetry.

### Completing Incomplete Curves
Develop algorithms to naturally complete 2D curves that have gaps due to occlusion removal. The project explores different levels of shape occlusion:
- **Fully Contained Shapes**: One shape completely inside another.
- **Partially Contained Shapes**: Shapes that are connected but partially occluded.
- **Disconnected Shapes**: Curves that are fragmented due to occlusion.

## Usage
To get started, clone this repository and use the provided Python scripts to read, process, and visualize curves. The scripts require `numpy` and `matplotlib` for processing and visualization, and `svgwrite` and `cairosvg` for rendering SVG outputs.


## Expected Results
The repository includes examples for various scenarios:
- **Isolated Curves**: Single polylines representing simple shapes.
- **Fragmented Shapes**: Complex shapes built from multiple polylines.
- **Occluded Shapes**: Shapes with partial or complete occlusion requiring completion.

## Evaluation
Regularization and symmetry are evaluated based on the number of regular geometric shapes and symmetry detected. For occlusion, rasterization techniques are used to ensure the correctness of curve completion.
