# System Graphs: Visualizing Latent Structures and Phenomenological Experiences

System Graphs is a visualization tool designed to help users explore and understand the latent structures and phenomenological experiences existing in their minds. By representing continuous cause-effect chains and relationships between different elements or phenomena, this application provides a unique perspective on how individuals conceptualize the world around them.

## Overview

The application allows users to define up to three dimensions, onto which they can graph sets of related elements. Users can create sets from arbitrary groups or elements within the graph, including other sets and combinations of sets and vectors, enabling flexible and customized groupings. Additionally, users can compact sets into lower dimensions, facilitating higher-dimensional analysis and revealing deeper insights. Connections between sets can be of arbitrary length, and are continuous, resembling a continuous manifold.

## Use

System Graphs are particularly well-suited for autognostic analysis of cause-effect and association analysis relating to life and mental health issues. It's useful to many people, as it does not impose a specific worldview or conceptual model. Instead, it's a tool that empowers users to develop their own models by visualizing relationships and interconnections between various aspects of existence.

## Features

- **Multidimensional Graphing**: Define arbitrary dimensions for visualizing relationships.
- **Set Creation**: Graph sets onto dimensions, representing collections of related elements, including other sets and combinations of sets and vectors.
- **Set Mapping**: Map sets arbitrarily to other sets.
- **Arbitrary Grouping**: Define sets from any elements within the graph, including other sets and combinations of sets and vectors.
- **Dimensional Preservation**: Represent sets as single-dimension patterns while preserving their inherent dimensions.
- **Multiple Views**: Simultaneous visualization of multiple dimensions.

## Implementation

Built with Rust, leveraging its performance, safety, and concurrency. Composed of modular objects:

1. **Vector**: Point in multidimensional space with x, y, z coordinates.
2. **Dimension**: Arbitrary dimension with name, unit, and scale.
3. **Set**: Collection of Vectors with manipulation methods, including the ability to create sets from other sets and combinations of sets and vectors.
4. **Graph**: Collection of Sets, with methods for creating, visualizing, and mapping sets across dimensions.
5. **View**: Renders and displays the graph in specific projections.
6. **Application**: Central object managing state, interactions, data, and UI. Coordinates object interactions.

## License

System Graphs is released under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html).
