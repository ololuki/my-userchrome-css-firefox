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

## Disable blocking Paste event on some text fields
```
dom.event.clipboardevents.enabled
```
Value to set to allow pasting:
```
false
```
