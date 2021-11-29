## BarChart

Display a simple single-line barchart. All items should represent a total of 100% within the bar.

## Features

Set listview context within the app and configure chart value (`Integer`) and value names (`string`).

Configure the colors that will be used for each item in the list. The widget uses an array of 6 default colors.

Both the bar legend and the bar chart segments can be hovered to see some additional information inside a tooltip.

Sorting options: The results can be sorted by name, value or even via custom attribute (`Integer`).

## Usage

1. Install NPM package dependencies by using: `npm install`. If you use NPM v7.x.x, which can be checked by executing
   `npm -v`, execute: `npm install --legacy-peer-deps`.
1. Run `npm start` to watch for code changes. On every change:
    - the widget will be bundled;
    - the bundle will be included in a `dist` folder in the root directory of the project;
    - the bundle will be included in the `deployment` and `widgets` folder of the Mendix test project.
