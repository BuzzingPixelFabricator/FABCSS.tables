# Fabricator Table Styling

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fabcss.tables --save`

If you are not using Fabricator, you will need to include into your Less build `src/FABCSS.tables.les`.

## Usage

Variables available in this file you can override:

```
@tableBordered: true;
@tableStriped: true;
@tableCellBorderColor: lighten(#000, 90%);
@tableStripedPosition: odd; // even, odd
@tableStripedBackground: lighten(#000, 96%);
@tableFontSize: false;
@tableMarginBottom: 20px;
@tableCellLineHeight: false;
@tableCellPaddingHorizontal: 16px;
@tableCellPaddingVertical: 6px;
@thColor: lighten(#000, 25%);
@tableCaptionBackground: lighten(#000, 96%);
@tableCaptionFontStyle: italic;
@tableCaptionPaddingVertical: 12px;
@tableCaptionPaddingHorizontal: @tableCellPaddingHorizontal;
```
