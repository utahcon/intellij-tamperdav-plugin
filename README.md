# TamperDAV (intellij-tamperdav-plugin)

This plugin provides ease of use for TamperMonkey developers by embedding TamperDAV control right into the IntelliJ 
IDEs. 

[//]: # (![Build]&#40;https://github.com/utahcon/intellij-tamperdav-plugin/workflows/Build/badge.svg&#41;)
[//]: # ([![Version]&#40;https://img.shields.io/jetbrains/plugin/v/PLUGIN_ID.svg&#41;]&#40;https://plugins.jetbrains.com/plugin/PLUGIN_ID&#41;)
[//]: # ([![Downloads]&#40;https://img.shields.io/jetbrains/plugin/d/PLUGIN_ID.svg&#41;]&#40;https://plugins.jetbrains.com/plugin/PLUGIN_ID&#41;)

## Links
- [IntelliJ Platform SDK](https://plugins.jetbrains.com/docs/intellij/key-topics.html)

## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [ ] Get familiar with the [template documentation][template].
- [ ] Verify the [pluginGroup](./gradle.properties), [plugin ID](./src/main/resources/META-INF/plugin.xml) and [sources package](./src/main/kotlin).
- [ ] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html).
- [ ] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [ ] Set the Plugin ID in the above README badges.
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.

<!-- Plugin description -->
This Fancy IntelliJ Platform Plugin is going to be your implementation of the brilliant ideas that you have.

This specific section is a source for the [plugin.xml](/src/main/resources/META-INF/plugin.xml) file which will be extracted by the [Gradle](/build.gradle.kts) during the build process.

To keep everything working, do not remove `<!-- ... -->` sections. 
<!-- Plugin description end -->

## Installation

- Using IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "intellij-tamperdav-plugin"</kbd> >
  <kbd>Install Plugin</kbd>
  
- Manually:

  Download the [latest release](https://github.com/utahcon/intellij-tamperdav-plugin/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
