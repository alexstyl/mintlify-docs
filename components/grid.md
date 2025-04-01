---
title: Grid
---

# Grid

Displays items from a [Data Source](/docs/building/data). Grids can display a large number of data effectively without
having to worry about the performance of your app.

![](/grid.png)

## The `Dynamic` component

Grids can contain a single child component, called `Dynamic`. Dynamic is a special element which is used as a
placeholder for every single row of your selected Google Sheet. Any change to the looks of the Dynamic component will
reflect the changes on every single row of your grid.

Dynamic elements can also be used to show content from [your linked Google Sheet](/docs/building/data)

### Displaying content from Google Sheets

1. Select the element inside of Dynamic where you want to show the content from Google Sheet (such as a `Text`)
2. Scroll to the **Content** property and click on the <img class='docs-icon' src="/assets/sliders.svg"> icon.
3. Select any column from your Google Sheet you want to be displayed.

To see real data flowing into your app, make sure to [preview your app](/docs/building/app-preview).

## Filtering Data

To show only part of your data into the Grid use the `Filter` property.

### How to show data from a specific category (static filtering)

1. Select your `Grid` and scroll to the `Filter` property.
2. Select a `Text Filter`.
3. Select the Google Sheet column you want to filter against (ie if you want to display products of a specific category
   choose "Category")
4. Enter the text the column must include in the `Cell must contain text` property.

That's it. To try out your filter, [preview your app](/docs/building/app-preview) and start typing into your search
field.

### How to build a search filter

1. Select the [Text Field](/docs/components/text-field) of your search.
2. Scroll down to its `Tag` property and enter a tag, such as "Search field".
3. Select your `Grid` and scroll to the `Filter` property.
4. Select a `Text Filter`.
5. Select the Google Sheet column you want to filter against (ie if you want to display products of a specific category
   choose "Category")
6. Click on the <img class='docs-icon' src="/assets/tags.svg"> icon and select your new tagged element "Search field".

That's it. To try out your filter, [preview your app](/docs/building/app-preview) and start typing into your search
field.

## Grid Properties

### Layout

|                          |                                                                |
|--------------------------|----------------------------------------------------------------|
| **Orientation**          | The direction of the items in the grid.                   |
| **Alignment**            | How items are lined up inside the grid on the main axis.  |
| **Arrangement**          | How items are organized in the grid on the opposite axis. |
| **Spacing**              | The space between items in the grid.                      |
| **Items per Column/Row** | How many items fit in each column or row of the grid.          |

### Data Source

|                 |                                                                                   |
|-----------------|-----------------------------------------------------------------------------------|
| **Data Source** | The Google Sheet from where to load the data from.                                |
| **Filter**      | Set a filter in order to display a selected number of rows from your Google Sheet |

## Dynamic Properties

The Dynamic element does not have any properties.

However, it enables its children
to [show dynamic data from the linked Google Sheet](#displaying-content-from-google-sheets).

## Default Properties

Every component has a set of default properties on top of their specific ones.

[Explore the full list of default properties](/docs/components)

## Designing responsive Screens

[Learn more about Tablet Design](/docs/building/tablet-overrides)
