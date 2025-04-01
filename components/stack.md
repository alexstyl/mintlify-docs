---
title: Stack
---

# Stack

Stack are one of core components in Paper and they are truly powerful. They are used to create horizontal and
vertical lists, grids of any items and scrollable lists.

They are also the core component when it comes to responsive design
using [Tablet Overrides](/docs/building/tablet-overrides).

Stacks display nothing by default (unless you specify a property such as a background color).

They are used to hold other elements (you can think of them as a group of elements) and control how they are laid out in
the screen.

For example, **a vertical list** of chat conversations is nothing more than a Stack with a **Vertical orientation**.

**A 3 column grid** is a Stack with a **Horizontal orientation**, that **Wraps** its contents and has **3 items
per row**.

Stacks can place their items one next to each other (horizontally or vertically) or on top of each other (stacked).

## Stack Properties

### Appearance

|                   |                                                           |
|-------------------|-----------------------------------------------------------|
| **Content color** | The color to apply to any Text or Icons within the Stack. |

### Layout

|                          |                                                                                                |
|--------------------------|------------------------------------------------------------------------------------------------|
| **Orientation**          | The direction of the items in the Stack.                                                       |
| **Alignment**            | How items are lined up inside the Stack on the main axis.                                      |
| **Arrangement**          | How items are organized in the Stack on the opposite axis.                                     |
| **Spacing**              | The space between items in the Stack.                                                          |
| **Lazy Loading**         | (Advanced) Whether the Stack's items need to be rendered only when they appear on the screen.  |
| **Wrap Contents**        | Whether items move to a new line or column when there's no more space in the Stack.            |
| **Items per Column/Row** | (Requires Lazy Loading or Wrap) How many items fit in each column or row of the Stack. |
| **Scroll Direction**     | The direction in which you can scroll within the Stack.                                        |

[Learn more about Tablet Design](/docs/building/tablet-overrides)
