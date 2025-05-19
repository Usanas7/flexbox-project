### 1. Basic Concepts

- **Flex Container**: The parent element that holds the flex items. It is defined by setting `display: flex` or `display: inline-flex`.
- **Flex Items**: The children of the flex container.

### 2. Flex Container Properties

- `display: flex;` - Defines a flex container.
- `flex-direction`: Defines the direction of the flex items.
  - `row` (default): left to right.
  - `row-reverse`: right to left.
  - `column`: top to bottom.
  - `column-reverse`: bottom to top.
- `flex-wrap`: Controls whether the flex items should wrap or not.
  - `nowrap` (default): all items will be on one line.
  - `wrap`: items will wrap onto multiple lines.
  - `wrap-reverse`: items will wrap onto multiple lines in reverse order.
- `justify-content`: Aligns flex items along the main axis.
  - `flex-start` (default): items are packed toward the start.
  - `flex-end`: items are packed toward the end.
  - `center`: items are centered.
  - `space-between`: items are evenly distributed with the first item at the start and the last item at the end.
  - `space-around`: items are evenly distributed with equal space around them.
- `align-items`: Aligns flex items along the cross axis.
  - `stretch` (default): items stretch to fill the container.
  - `flex-start`: items are aligned at the start.
  - `flex-end`: items are aligned at the end.
  - `center`: items are centered.
  - `baseline`: items are aligned at their baseline.
- `align-content`: Aligns flex lines when there is extra space in the cross axis.
  - `stretch` (default): lines stretch to fill the container.
  - `flex-start`: lines are packed toward the start.
  - `flex-end`: lines are packed toward the end.
  - `center`: lines are centered.
  - `space-between`: lines are evenly distributed.
  - `space-around`: lines are evenly distributed with equal space around them.

### 3. Flex Item Properties

- `order`: Controls the order of the flex items.
- `flex-grow`: Defines the ability for a flex item to grow if necessary.
- `flex-shrink`: Defines the ability for a flex item to shrink if necessary.
- `flex-basis`: Defines the default size of an element before the remaining space is distributed.
- `align-self`: Allows the default alignment (or the one specified by `align-items`) to be overridden for individual flex items.
