# build-watch
Build a project when the source files are updated.

## How to use
* Move to your project main directory containing the source files.
* Run `build-watch <BUILD-COMMAND>`.

## Key concept : source file state
Every files in the build-watch directory is considered as a source file. This is intended as a clean way to structure a project, and keep source files separated from binaries and other intermediary built files. If a file is generated within the source files during the build step, the project will infinitly rebuild.
