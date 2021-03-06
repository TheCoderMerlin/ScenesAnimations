# ScenesAnimations

ScenesAnimations is a library built on top of Igis and Scenes with added support for running animations.

## Table of Content
- [Setup](#setup)
- [Documentation](#documentation)
- [Project Roadmap](#project-roadmap)

## Setup

To use the ScenesAnimations library in your existing Scenes project, add the following line to your `dylib.manifest` file:

```shell
ScenesAnimations          <version>
```

Then, run the following commands on the command line:

```shell
rm dir-locals.el
dylibEmacs
build
```

## Documentation

Coming Soon!

## Project Roadmap
- Add Documentation to README.
- Add Interpolatable support for characters and strings.
- Make Color HSB Interpolatable.
- Add support for animating along a path.
- Add simplified declarative syntax for animating properties.
- Add Animation Timelines.
- Add Animation event handlers?
- Add prefabricated animations
- Add animation fill mode (refer to CSS Animations)
