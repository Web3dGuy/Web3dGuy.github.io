# Monaco Editor Complete Color Settings Reference

This document provides a comprehensive list of all Monaco Editor theme color settings that can be used with `monaco.editor.defineTheme()`.

## Basic Editor Colors

### Core Editor
- `editor.background` - Editor background color
- `editor.foreground` - Editor default foreground color
- `editorLineNumber.foreground` - Color of editor line numbers
- `editorLineNumber.activeForeground` - Color of the active editor line number
- `editorLineNumber.dimmedForeground` - Color of the final editor line when renderFinalNewline is dimmed

### Cursor
- `editorCursor.foreground` - Color of the editor cursor
- `editorCursor.background` - Background color of the editor cursor (for block cursor)
- `editorMultiCursor.primary.foreground` - Color of the primary cursor when multiple cursors are present
- `editorMultiCursor.primary.background` - Background color of the primary cursor when multiple cursors are present
- `editorMultiCursor.secondary.foreground` - Color of secondary cursors when multiple cursors are present
- `editorMultiCursor.secondary.background` - Background color of secondary cursors when multiple cursors are present

### Selection
- `editor.selectionBackground` - Color of the editor selection
- `editor.selectionForeground` - Color of the selected text for high contrast
- `editor.inactiveSelectionBackground` - Color of the selection in an inactive editor
- `editor.selectionHighlightBackground` - Color for regions with the same content as the selection
- `editor.selectionHighlightBorder` - Border color for regions with the same content as the selection

### Find/Search
- `editor.findMatchBackground` - Color of the current search match
- `editor.findMatchForeground` - Text color of the current search match
- `editor.findMatchBorder` - Border color of the current search match
- `editor.findMatchHighlightBackground` - Color of the other search matches
- `editor.findMatchHighlightForeground` - Foreground color of the other search matches
- `editor.findMatchHighlightBorder` - Border color of the other search matches
- `editor.findRangeHighlightBackground` - Color the range limiting the search
- `editor.findRangeHighlightBorder` - Border color the range limiting the search

### Word Highlighting
- `editor.wordHighlightBackground` - Background color of a symbol during read-access
- `editor.wordHighlightBorder` - Border color of a symbol during read-access
- `editor.wordHighlightStrongBackground` - Background color of a symbol during write-access
- `editor.wordHighlightStrongBorder` - Border color of a symbol during write-access
- `editor.wordHighlightTextBackground` - Background color of a textual occurrence for a symbol
- `editor.wordHighlightTextBorder` - Border color of a textual occurrence for a symbol

### Line Highlighting
- `editor.lineHighlightBackground` - Background color for the highlight of line at the cursor position
- `editor.lineHighlightBorder` - Background color for the border around the line at the cursor position

### Hover
- `editor.hoverHighlightBackground` - Highlight below the word for which a hover is shown

### Links
- `editorLink.activeForeground` - Color of active links

### Range Highlighting
- `editor.rangeHighlightBackground` - Background color of highlighted ranges
- `editor.rangeHighlightBorder` - Background color of the border around highlighted ranges

### Symbol Highlighting
- `editor.symbolHighlightBackground` - Background color of highlighted symbol
- `editor.symbolHighlightBorder` - Background color of the border around highlighted symbols

### Whitespace
- `editorWhitespace.foreground` - Color of whitespace characters in the editor

### Indentation Guides
- `editorIndentGuide.background` - Color of the editor indentation guides
- `editorIndentGuide.background1` - Color of the editor indentation guides (1)
- `editorIndentGuide.background2` - Color of the editor indentation guides (2)
- `editorIndentGuide.background3` - Color of the editor indentation guides (3)
- `editorIndentGuide.background4` - Color of the editor indentation guides (4)
- `editorIndentGuide.background5` - Color of the editor indentation guides (5)
- `editorIndentGuide.background6` - Color of the editor indentation guides (6)
- `editorIndentGuide.activeBackground` - Color of the active editor indentation guide
- `editorIndentGuide.activeBackground1` - Color of the active editor indentation guides (1)
- `editorIndentGuide.activeBackground2` - Color of the active editor indentation guides (2)
- `editorIndentGuide.activeBackground3` - Color of the active editor indentation guides (3)
- `editorIndentGuide.activeBackground4` - Color of the active editor indentation guides (4)
- `editorIndentGuide.activeBackground5` - Color of the active editor indentation guides (5)
- `editorIndentGuide.activeBackground6` - Color of the active editor indentation guides (6)

### Rulers
- `editorRuler.foreground` - Color of the editor rulers

### Folding
- `editor.foldBackground` - Background color for folded ranges
- `editor.foldPlaceholderForeground` - Color of the collapsed text after the first line of a folded range

### Unicode Highlighting
- `editorUnicodeHighlight.border` - Border color used to highlight unicode characters
- `editorUnicodeHighlight.background` - Background color used to highlight unicode characters

### Composition
- `editor.compositionBorder` - The border color for an IME composition

### Placeholder
- `editor.placeholder.foreground` - Foreground color of the placeholder text in the editor

### Linked Editing
- `editor.linkedEditingBackground` - Background color when the editor is in linked editing mode

## Error/Warning/Info Highlighting

### Errors
- `editorError.foreground` - Foreground color of error squiggles in the editor
- `editorError.border` - Border color of error boxes in the editor
- `editorError.background` - Background color of error text in the editor

### Warnings
- `editorWarning.foreground` - Foreground color of warning squiggles in the editor
- `editorWarning.border` - Border color of warning boxes in the editor
- `editorWarning.background` - Background color of warning text in the editor

### Information
- `editorInfo.foreground` - Foreground color of info squiggles in the editor
- `editorInfo.border` - Border color of info boxes in the editor
- `editorInfo.background` - Background color of info text in the editor

### Hints
- `editorHint.foreground` - Foreground color of hints in the editor
- `editorHint.border` - Border color of hint boxes in the editor

### Unnecessary Code
- `editorUnnecessaryCode.border` - Border color of unnecessary (unused) source code
- `editorUnnecessaryCode.opacity` - Opacity of unnecessary (unused) source code

## Widget Colors

### General Widget
- `editorWidget.foreground` - Foreground color of editor widgets
- `editorWidget.background` - Background color of editor widgets
- `editorWidget.border` - Border color of the editor widget
- `editorWidget.resizeBorder` - Border color of the resize bar of editor widgets

### Suggestion Widget
- `editorSuggestWidget.background` - Background color of the suggestion widget
- `editorSuggestWidget.border` - Border color of the suggestion widget
- `editorSuggestWidget.foreground` - Foreground color of the suggestion widget
- `editorSuggestWidget.focusHighlightForeground` - Color of the match highlights when an item is focused
- `editorSuggestWidget.highlightForeground` - Color of the match highlights in the suggestion widget
- `editorSuggestWidget.selectedBackground` - Background color of the selected entry
- `editorSuggestWidget.selectedForeground` - Foreground color of the selected entry
- `editorSuggestWidget.selectedIconForeground` - Icon foreground color of the selected entry
- `editorSuggestWidgetStatus.foreground` - Foreground color of the suggest widget status

### Hover Widget
- `editorHoverWidget.foreground` - Foreground color of the editor hover
- `editorHoverWidget.background` - Background color of the editor hover
- `editorHoverWidget.border` - Border color of the editor hover
- `editorHoverWidget.highlightForeground` - Foreground color of the active item in the parameter hint
- `editorHoverWidget.statusBarBackground` - Background color of the editor hover status bar

### Parameter Hint Widget
- `editorHoverWidget.statusBarBackground` - Background color of the parameter hint status bar

## Bracket Matching & Colorization

### Bracket Matching
- `editorBracketMatch.background` - Background color behind matching brackets
- `editorBracketMatch.border` - Color for matching brackets boxes

### Bracket Pair Colorization
- `editorBracketHighlight.foreground1` - Foreground color of brackets (1)
- `editorBracketHighlight.foreground2` - Foreground color of brackets (2)
- `editorBracketHighlight.foreground3` - Foreground color of brackets (3)
- `editorBracketHighlight.foreground4` - Foreground color of brackets (4)
- `editorBracketHighlight.foreground5` - Foreground color of brackets (5)
- `editorBracketHighlight.foreground6` - Foreground color of brackets (6)
- `editorBracketHighlight.unexpectedBracket.foreground` - Foreground color of unexpected brackets

### Bracket Pair Guides
- `editorBracketPairGuide.activeBackground1` - Background color of active bracket pair guides (1)
- `editorBracketPairGuide.activeBackground2` - Background color of active bracket pair guides (2)
- `editorBracketPairGuide.activeBackground3` - Background color of active bracket pair guides (3)
- `editorBracketPairGuide.activeBackground4` - Background color of active bracket pair guides (4)
- `editorBracketPairGuide.activeBackground5` - Background color of active bracket pair guides (5)
- `editorBracketPairGuide.activeBackground6` - Background color of active bracket pair guides (6)
- `editorBracketPairGuide.background1` - Background color of inactive bracket pair guides (1)
- `editorBracketPairGuide.background2` - Background color of inactive bracket pair guides (2)
- `editorBracketPairGuide.background3` - Background color of inactive bracket pair guides (3)
- `editorBracketPairGuide.background4` - Background color of inactive bracket pair guides (4)
- `editorBracketPairGuide.background5` - Background color of inactive bracket pair guides (5)
- `editorBracketPairGuide.background6` - Background color of inactive bracket pair guides (6)

## Editor Groups & Tabs

### Editor Groups
- `editorGroup.border` - Color to separate multiple editor groups from each other
- `editorGroup.dropBackground` - Background color when dragging editors around
- `editorGroup.emptyBackground` - Background color of an empty editor group
- `editorGroup.focusedEmptyBorder` - Border color of an empty editor group that is focused

### Editor Group Header
- `editorGroupHeader.noTabsBackground` - Background color of the editor group title header when using single Tab
- `editorGroupHeader.tabsBackground` - Background color of the Tabs container
- `editorGroupHeader.tabsBorder` - Border color below the editor tabs control when tabs are enabled
- `editorGroupHeader.border` - Border color between editor group header and editor

### Tab Colors
- `tab.activeBackground` - Active Tab background color in an active group
- `tab.activeForeground` - Active Tab foreground color in an active group
- `tab.activeBorder` - Bottom border for the active tab
- `tab.activeBorderTop` - Top border for the active tab
- `tab.inactiveBackground` - Inactive Tab background color
- `tab.inactiveForeground` - Inactive Tab foreground color in an active group
- `tab.border` - Border to separate Tabs from each other
- `tab.hoverBackground` - Tab background color when hovering
- `tab.hoverForeground` - Tab foreground color when hovering
- `tab.hoverBorder` - Border to highlight tabs when hovering
- `tab.lastPinnedBorder` - Border on the right of the last pinned editor
- `tab.dragAndDropBorder` - Border between tabs to indicate that a tab can be inserted

### Unfocused Group Tabs
- `tab.unfocusedActiveBackground` - Active Tab background color in an inactive editor group
- `tab.unfocusedActiveForeground` - Active tab foreground color in an inactive editor group
- `tab.unfocusedActiveBorder` - Bottom border for the active tab in an inactive editor group
- `tab.unfocusedActiveBorderTop` - Top border for the active tab in an inactive editor group
- `tab.unfocusedInactiveBackground` - Inactive Tab background color in an unfocused group
- `tab.unfocusedInactiveForeground` - Inactive tab foreground color in an inactive editor group
- `tab.unfocusedHoverBackground` - Tab background color in an unfocused group when hovering
- `tab.unfocusedHoverForeground` - Tab foreground color in an unfocused group when hovering
- `tab.unfocusedHoverBorder` - Border to highlight tabs in an unfocused group when hovering

### Modified Tabs
- `tab.activeModifiedBorder` - Border on the top of modified (dirty) active tabs in an active group
- `tab.inactiveModifiedBorder` - Border on the top of modified (dirty) inactive tabs in an active group
- `tab.unfocusedActiveModifiedBorder` - Border on the top of modified (dirty) active tabs in an unfocused group
- `tab.unfocusedInactiveModifiedBorder` - Border on the top of modified (dirty) inactive tabs in an unfocused group

### Side-by-Side Editor
- `sideBySideEditor.horizontalBorder` - Color to separate two editors when shown side by side from top to bottom
- `sideBySideEditor.verticalBorder` - Color to separate two editors when shown side by side from left to right

## Minimap

### Minimap Main
- `minimap.background` - Minimap background color
- `minimap.foregroundOpacity` - Opacity of foreground elements rendered in the minimap
- `minimap.selectionHighlight` - Highlight color for the editor selection
- `minimap.selectionOccurrenceHighlight` - Minimap marker color for repeating editor selections
- `minimap.findMatchHighlight` - Highlight color for matches from search within files
- `minimap.errorHighlight` - Highlight color for errors within the editor
- `minimap.warningHighlight` - Highlight color for warnings within the editor
- `minimap.infoHighlight` - Minimap marker color for infos

### Minimap Slider
- `minimapSlider.background` - Minimap slider background color
- `minimapSlider.hoverBackground` - Minimap slider background color when hovering
- `minimapSlider.activeBackground` - Minimap slider background color when clicked on

### Minimap Gutter
- `minimapGutter.addedBackground` - Minimap gutter color for added content
- `minimapGutter.modifiedBackground` - Minimap gutter color for modified content
- `minimapGutter.deletedBackground` - Minimap gutter color for deleted content

## Overview Ruler

### Overview Ruler Main
- `editorOverviewRuler.background` - Background color of the editor overview ruler
- `editorOverviewRuler.border` - Color of the overview ruler border
- `editorOverviewRuler.findMatchForeground` - Overview ruler marker color for find matches
- `editorOverviewRuler.rangeHighlightForeground` - Overview ruler marker color for highlighted ranges
- `editorOverviewRuler.selectionHighlightForeground` - Overview ruler marker color for selection highlights
- `editorOverviewRuler.wordHighlightForeground` - Overview ruler marker color for symbol highlights
- `editorOverviewRuler.wordHighlightStrongForeground` - Overview ruler marker color for write-access symbol highlights
- `editorOverviewRuler.wordHighlightTextForeground` - Overview ruler marker color of a textual occurrence for a symbol

### Overview Ruler Modifications
- `editorOverviewRuler.modifiedForeground` - Overview ruler marker color for modified content
- `editorOverviewRuler.addedForeground` - Overview ruler marker color for added content
- `editorOverviewRuler.deletedForeground` - Overview ruler marker color for deleted content

### Overview Ruler Errors
- `editorOverviewRuler.errorForeground` - Overview ruler marker color for errors
- `editorOverviewRuler.warningForeground` - Overview ruler marker color for warnings
- `editorOverviewRuler.infoForeground` - Overview ruler marker color for infos

### Overview Ruler Other
- `editorOverviewRuler.bracketMatchForeground` - Overview ruler marker color for matching brackets

## Gutter

### Gutter Main
- `editorGutter.background` - Background color of the editor gutter
- `editorGutter.modifiedBackground` - Editor gutter background color for lines that are modified
- `editorGutter.addedBackground` - Editor gutter background color for lines that are added
- `editorGutter.deletedBackground` - Editor gutter background color for lines that are deleted
- `editorGutter.commentRangeForeground` - Editor gutter decoration color for commenting ranges
- `editorGutter.commentGlyphForeground` - Editor gutter decoration color for commenting glyphs
- `editorGutter.commentUnresolvedGlyphForeground` - Editor gutter decoration color for unresolved comment threads
- `editorGutter.foldingControlForeground` - Color of the folding control in the editor gutter

## Diff Editor

### Diff Editor Main
- `diffEditor.border` - Border color between the two text editors
- `diffEditor.diagonalFill` - Color of the diff editor's diagonal fill

### Diff Editor Insertions
- `diffEditor.insertedTextBackground` - Background color for text that got inserted
- `diffEditor.insertedTextBorder` - Outline color for the text that got inserted
- `diffEditor.insertedLineBackground` - Background color for lines that got inserted

### Diff Editor Deletions
- `diffEditor.removedTextBackground` - Background color for text that got removed
- `diffEditor.removedTextBorder` - Outline color for text that got removed
- `diffEditor.removedLineBackground` - Background color for lines that got removed

### Diff Editor Gutter
- `diffEditorGutter.insertedLineBackground` - Background color for the margin where lines got inserted
- `diffEditorGutter.removedLineBackground` - Background color for the margin where lines got removed

### Diff Editor Overview
- `diffEditorOverview.insertedForeground` - Diff overview ruler foreground for inserted content
- `diffEditorOverview.removedForeground` - Diff overview ruler foreground for removed content

### Diff Editor Unchanged Regions
- `diffEditor.unchangedRegionBackground` - The color of unchanged blocks in diff editor
- `diffEditor.unchangedRegionForeground` - The foreground color of unchanged blocks in the diff editor
- `diffEditor.unchangedRegionShadow` - The color of the shadow around unchanged region widgets
- `diffEditor.unchangedCodeBackground` - The background color of unchanged code in the diff editor

### Diff Editor Move
- `diffEditor.move.border` - The border color for text that got moved in the diff editor
- `diffEditor.moveActive.border` - The active border color for text that got moved in the diff editor

## InlayHints

### Inlay Hints Main
- `editorInlayHint.background` - Background color of inline hints
- `editorInlayHint.foreground` - Foreground color of inline hints

### Inlay Hints Types
- `editorInlayHint.typeForeground` - Foreground color of inline hints for types
- `editorInlayHint.typeBackground` - Background color of inline hints for types

### Inlay Hints Parameters
- `editorInlayHint.parameterForeground` - Foreground color of inline hints for parameters
- `editorInlayHint.parameterBackground` - Background color of inline hints for parameters

## CodeLens

### CodeLens
- `editorCodeLens.foreground` - Foreground color of an editor CodeLens

## Lightbulb

### Lightbulb
- `editorLightBulb.foreground` - The color used for the lightbulb actions icon
- `editorLightBulbAutoFix.foreground` - The color used for the lightbulb auto fix actions icon
- `editorLightBulbAi.foreground` - The color used for the lightbulb AI icon

## Ghost Text

### Ghost Text
- `editorGhostText.background` - Background color of the ghost text in the editor
- `editorGhostText.foreground` - Foreground color of the ghost text shown by inline completion providers
- `editorGhostText.border` - Border color of the ghost text shown by inline completion providers

## Sticky Scroll

### Sticky Scroll
- `editorStickyScroll.background` - Editor sticky scroll background color
- `editorStickyScroll.border` - Border color of sticky scroll in the editor
- `editorStickyScroll.shadow` - Shadow color of sticky scroll in the editor
- `editorStickyScrollHover.background` - Editor sticky scroll on hover background color

## Navigation Widgets

### Editor Marker Navigation
- `editorMarkerNavigation.background` - Editor marker navigation widget background
- `editorMarkerNavigationError.background` - Editor marker navigation widget error color
- `editorMarkerNavigationWarning.background` - Editor marker navigation widget warning color
- `editorMarkerNavigationInfo.background` - Editor marker navigation widget info color
- `editorMarkerNavigationError.headerBackground` - Editor marker navigation widget error heading background
- `editorMarkerNavigationWarning.headerBackground` - Editor marker navigation widget warning heading background
- `editorMarkerNavigationInfo.headerBackground` - Editor marker navigation widget info heading background

## Debug Widget

### Debug Exception Widget
- `debugExceptionWidget.background` - Exception widget background color
- `debugExceptionWidget.border` - Exception widget border color

## Peek View

### Peek View Main
- `peekView.border` - Color of the peek view borders and arrow
- `peekViewTitle.background` - Background color of the peek view title area
- `peekViewTitleLabel.foreground` - Color of the peek view title
- `peekViewTitleDescription.foreground` - Color of the peek view title info

### Peek View Editor
- `peekViewEditor.background` - Background color of the peek view editor
- `peekViewEditorGutter.background` - Background color of the gutter in the peek view editor
- `peekViewEditor.matchHighlightBackground` - Match highlight color in the peek view editor
- `peekViewEditor.matchHighlightBorder` - Match highlight border color in the peek view editor

### Peek View Result
- `peekViewResult.background` - Background color of the peek view result list
- `peekViewResult.fileForeground` - Foreground color for file nodes in the peek view result list
- `peekViewResult.lineForeground` - Foreground color for line nodes in the peek view result list
- `peekViewResult.matchHighlightBackground` - Match highlight color in the peek view result list
- `peekViewResult.selectionBackground` - Background color of the selected entry in the peek view result list
- `peekViewResult.selectionForeground` - Foreground color of the selected entry in the peek view result list

## Merge Conflicts

### Merge Conflicts Main
- `merge.border` - Border color on headers and the splitter in inline merge conflicts

### Current Header/Content
- `merge.currentHeaderBackground` - Current header background in inline merge conflicts
- `merge.currentContentBackground` - Current content background in inline merge conflicts

### Incoming Header/Content
- `merge.incomingHeaderBackground` - Incoming header background in inline merge conflicts
- `merge.incomingContentBackground` - Incoming content background in inline merge conflicts

### Common Ancestor
- `merge.commonHeaderBackground` - Common ancestor header background in inline merge-conflicts
- `merge.commonContentBackground` - Common ancestor content background in inline merge-conflicts

### Merge Overview Ruler
- `editorOverviewRuler.currentContentForeground` - Current overview ruler foreground for inline merge conflicts
- `editorOverviewRuler.incomingContentForeground` - Incoming overview ruler foreground for inline merge conflicts
- `editorOverviewRuler.commonContentForeground` - Common ancestor overview ruler foreground for inline merge conflicts

## Watermark

### Watermark
- `editorWatermark.foreground` - Foreground color for the labels in the editor watermark

## List and Tree Colors (for Editor Context)

### Selection Background
- `list.activeSelectionBackground` - List/Tree background color for the selected item when active
- `list.activeSelectionForeground` - List/Tree foreground color for the selected item when active
- `list.inactiveSelectionBackground` - List/Tree background color for the selected item when inactive
- `list.inactiveSelectionForeground` - List/Tree foreground color for the selected item when inactive

### Focus Colors
- `list.focusBackground` - List/Tree background color for the focused item when active
- `list.focusForeground` - List/Tree foreground color for the focused item when active
- `list.focusOutline` - List/Tree outline color for the focused item when active

### Hover Colors
- `list.hoverBackground` - List/Tree background when hovering over items using the mouse
- `list.hoverForeground` - List/Tree foreground when hovering over items using the mouse

### Highlight Colors
- `list.highlightForeground` - List/Tree foreground color of the match highlights when searching
- `list.focusHighlightForeground` - List/Tree foreground color of the match highlights on actively focused items

### Drop Colors
- `list.dropBackground` - List/Tree drag and drop background when moving items around

### Filter Widget
- `listFilterWidget.background` - List/Tree Filter background color of typed text when searching
- `listFilterWidget.outline` - List/Tree Filter Widget's outline color of typed text when searching
- `listFilterWidget.noMatchesOutline` - List/Tree Filter Widget's outline color when no match is found

## Usage Examples

### Basic Dark Theme
```javascript
monaco.editor.defineTheme('custom-dark', {
  base: 'vs-dark',
  inherit: true,
  colors: {
    'editor.background': '#2a2f3a',
    'editor.foreground': '#e5e7eb',
    'editorCursor.foreground': '#22c55e',
    'editor.selectionBackground': '#22c55e40',
    'editor.lineHighlightBackground': '#3e3d32',
  }
});
```

### Custom Minimap Colors
```javascript
monaco.editor.defineTheme('custom-minimap', {
  base: 'vs-dark',
  inherit: true,
  colors: {
    'minimap.background': '#374151',
    'minimapSlider.background': '#22c55e40',
    'minimapSlider.hoverBackground': '#22c55e60',
    'minimapSlider.activeBackground': '#22c55e80',
  }
});
```

### Error/Warning Styling
```javascript
monaco.editor.defineTheme('custom-errors', {
  base: 'vs-dark',
  inherit: true,
  colors: {
    'editorError.foreground': '#ef4444',
    'editorWarning.foreground': '#f59e0b',
    'editorInfo.foreground': '#3b82f6',
    'editorHint.foreground': '#22c55e',
  }
});
``` 