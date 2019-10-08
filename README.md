# RUNX

Script for running multiple applications in one window with multiple terminals.

## Usage:

Create `Procfile.dev` file with following content:

```
p1: /path/to/app param1 param2
p2: /path/to/another/app params
```

And run `runx`. Every line will be executed in a subwindow of a main window.

