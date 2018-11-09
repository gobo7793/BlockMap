# Changelog

## Version 1.1.1
### Changes
- Support for changing the color map as well as the shader through CLI options
- Added an option to render chunks only if needed, called `--lazy`. (Implements #1)
- Fixed a few CLI bugs

### Known issues
- The about/help dialog still does nothing yet

## Version 1.1.0
### Changes
- Support for multiple color maps
- New color maps: No foliage, ocean ground, cave view
- Support for different shaders
- New height shading options: None, relief, biome color, height map
- GUI overhaul
- Made rendering of stacked semi-transparent blocks of the same color way faster
- Restructured gradle project structure

### Known bugs
- The about/help dialog does nothing yet

### Fixed bugs
- Crash when selecting folder and Minecraft ist not installed

## Version 1.0.1
### Changes
- CLI now actually works
- Added some simple relief shading to improve readability. The map does not look flat anymore.
- A toggle and more shaders are yet to come

### Known bugs
- There are some chunk-sized artifacts in the shading. This seems to come from chunks that have not been fully generated yet.