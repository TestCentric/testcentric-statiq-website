Description: Explains commands available in the context menu displayed by the test tree.
Order: 3
---
<!-- Page-specific styles -->
<style>
    img {float: right; margin-left: 20px; margin-bottom: 20px}
</style>

<div class="notice">
    Page under development. Needs revision for TestCentric GUI Version 2.
</div>

The context menu is displayed when one of the tree nodes is right-clicked.

![Context Menu](../img/contextmenu.png)

## Run
Runs the selected test - disabled if a test is running.

## Show Failed Assumptions
Turns on and off the display of cases under a **Theory** that have failed
an assumption (Inconclusive results). This menu item is only displayed for
nodes that are part of a **Theory**.

## Show Checkboxes
Turns the display of checkboxes in the tree on or off. The checkboxes may
be used to select multiple tests for running.

## Expand All
Expands all the nodes in the tree.

## Collapse All
Collapses all the nodes in the tree.

## Hide Tests
Expands nodes in the tree as far as fixtures only, hiding the tests under each fixture. 

## Properties
Displays the [Test Properties](./test-properties.html) for the selected test node.
