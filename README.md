# dircontent2byteslice

A dead simple tool to embed a file to Go.

```
Usage of dircontent2byteslice:
  -buildtags string
        build tags
  -compress
        use gzip compression
  -inputDir string
        inputDir dirpath
  -outputDir string
        outputDir dirpath
  -package string
        package name (default "main")
```

## How to use

```sh
dircontent2byteslice -inputDir INPUT_DIR_PATH -outputDir OUTPUT_DIR_PATH -package PACKAGE_NAME
```
