# List of changes in about:config

## Disable "File not downloaded: Potential security risk."
Is annoying users since around Firefox 93
```
dom.block_download_insecure
```
Value to set:
```
false
```

## Prevent text deselection on middle button click
This option was introduced around Firefox 93, for earlier versions use: https://github.com/ololuki/AutoScroll
```
general.autoscroll.prevent_to_collapse_selection_by_middle_mouse_down
```
Value to set:
```
true
```

## Disable dark background
Is annoing users since around Firefox 97
```
layout.css.prefers-color-scheme.content-override
```
Value to set to force light background:
```
1
```
More info: https://support.mozilla.org/en-US/questions/1364263

## Disable blocking Paste event on some text fields (optional - change this value only on broken sites that blocks copy paste on text field)
```
dom.event.clipboardevents.enabled
```
Value to set to allow pasting:
```
false
```

## Use temp directory for temporary files and download directory for downloaded files
Is annoying users since around Firefox 97 when mozilla forces you to mix temporary crap with wanted downloaded files in the same directory without asking.
```
browser.download.improvements_to_download_panel
```
Since Firefox 102 replaced with:
```
browser.download.start_downloads_in_tmp_dir
```
Value to set to prevent mixing crap with wanted files and use temp directory for temp files:
```
false
```

## Use old, small private window indicator
Is annoying users since around Firefox 106 when mozilla decided that very big and long text inside tabs bar is a good idea.
```
browser.privatebrowsing.enable-new-indicator
```
Value to set to have small indicator instead of big, long text that steals place for opened tabs:
```
false
```

## Disable "Extensions" button
Is annoying users since around Firefox 109, when mozilla decided that forcing unmovable and never needed button on main bar is a good idea.
```
extensions.unifiedExtensions.enabled
```
Value to set to disable this button:
```
false
```
