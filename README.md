# ChromaGraph: Four-Color Map Solver

A Python implementation of the map coloring constraint satisfaction problem based on the Four Color Theorem.

## Overview

ChromaGraph solves the classic map coloring problem using constraint satisfaction techniques. The Four Color Theorem states that any map can be colored using at most four colors such that no adjacent regions share the same color.

This project implements a constraint satisfaction solver that:
- Represents regions as nodes in a graph
- Models adjacency between regions as edges
- Applies constraint propagation algorithms to find valid colorings
- Visualizes the resulting colored maps using NetworkX

## Features

- Graph-based representation of map regions
- Efficient constraint satisfaction algorithm implementation
- Support for various map configurations
- Visualization of colored maps
- Built-in example with Connecticut regions

## Prerequisites

```
python >= 3.6
networkx
matplotlib
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Based on the Four Color Theorem
- Uses NetworkX for graph representation and visualization