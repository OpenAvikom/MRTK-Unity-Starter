# MRTK-Unity-Starter - A preconfigured Unity project for developing Mixed Reality applications

## Components

* Unity Version 2019.4.20f1
* Microsoft Mixed Reality Toolkit Version 2.5.4

## Configuration

* The project contains a [configuration](.gitattributes) for [Git Large File Storage](https://git-lfs.github.com/) support to enable efficient version management of large media files which are common for Unity projects.
* Furthermore, the [.gitignore](.gitignore) file excludes files generated by Unity from version control. However, this file should be reviewed when a new project is forked. Committing assets generated by the Mixed Reality Toolkit or VS Code configurations might be necessary to enable collaborative development.

## Adding Spatial Audio Support for HoloLens 2

If you want to add hardware-accelerated [Spatial Audio](https://github.com/microsoft/spatialaudio-unity) to your HoloLens 2 project, just add the following line to your [manifest.json](Packages/manifest.json):

```json
  "dependencies": {
      "com.microsoft.spatialaudio.spatializer.unity": "1.0.176",
      "com.microsoft.mixedreality.toolkit.examples": ...
```
