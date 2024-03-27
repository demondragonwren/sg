# System Graphs: Visualizing Latent Structures and Phenomenological Experiences

System Graphs is a powerful visualization tool designed to help users explore and understand the latent structures and phenomenological experiences existing in their minds. By representing continuous cause-effect chains and the relationships between different elements or phenomena, this application provides a unique perspective on how individuals conceptualize the world around them.

## Overview

The application allows users to define up to three dimensions, onto which they can graph sets of related elements. These sets can be created from arbitrary groups or elements within the graph, enabling flexible and customized groupings. Additionally, users can compact sets into lower dimensions, facilitating higher-dimensional analysis and revealing deeper insights. Connections between sets can be of arbatrary or specified lemgth, and are continous.

In the end, system graphs allow for extremely good visulization and analysis of higher dimentional structures. And combined with the arbatrary connections, this starts resembeling a continous manifold.

## Use

System Graphs are particularly well-suited for autognostic analysis of cause-effect and assoctiation analysis relating to both life, and mental health issues. It's useful to a great many people, as it does not impose a specific worldview or conceptual model. Instead, it's simply a tool that empowers users to develop their own models by visualizing the relationships and interconnections between various aspects of existance.

## Features

- **Multidimensional Graphing**: Define arbitrary dimensions for visualizing relationships.
- **Set Creation**: Graph sets onto dimensions, representing collections of related elements.
- **Set Mapping**: Map sets arbatrarily to other sets.
- **Set Connection**: Connect any set in any dimention to any other set in any other dimention.
- **Arbitrary Grouping**: Define sets from any elements within the graph.
- **Dimensional Preservation**: Represent sets as single-dimension patterns while preserving their inherent dimensions.
- **Multiple Views**: Simultaneous visualization of multiple dimensions.

## Implementation

Built with Rust, leveraging its performance, safety, and concurrency. Composed of modular objects:

1. **Vector**: Point in multidimensional space with x, y, z coordinates.
2. **Dimension**: Arbitrary dimension with name, unit, and scale.
3. **Set**: Collection of Vectors with manipulation methods.
4. **Graph**: Collection of Sets, with methods for creating, visualizing, and mapping sets across dimensions.
5. **View**: Renders and displays the graph in specific projections.
6. **Application**: Central object managing state, interactions, data, and UI. Coordinates object interactions.

## License

System Graphs is released under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html).
