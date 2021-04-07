# Paper Lineage

[Paper Lineage](https://paper-lineage.netlify.app/) is a visualization tool for finding the lineage of academic papers.
The main usage is to quickly identify papers and their direct influences, in order to understand the creation process of each paper.
The data is manually curated.

Paper Lineage is different from other citation-based tools, such as [Inciteful](https://inciteful.xyz) and [Connected Papers](https://www.connectedpapers.com).
These tools are good at finding comprehensive list of similar papers for rounding out literature review.
Paper Lineage is designed for finding only a handful of most relevant papers when exploring a new research topic.

## Data & Contribution

The data is manually curated and stored as a [JSON file](https://github.com/belinghy/paper-lineage/blob/main/lineage.json).
Please contribute by making a pull request, or open an issue to request for papers.

Before making a pull request, please make sure to read the following guidelines for creating lineage trees.

- Check if the corresponding paper is already in the database. If so, modify the tree, or else add a new tree.
  - Keep the number of nodes to a minimum, ideally less than 10
  - Max tree _width_ and _depth_ should not exceed 5 and 4 respectively
- `title` should include publication year at the end
- `link` should preferably point to open access PDF; if not available, then point to publisher's website or author's project website
- `description` provides additional context, but is not required
