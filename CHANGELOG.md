# Provider Architecture

## [1.0.0] - Initial Release

Added the widgets required to implement the FilledStacks architectures using Provider and the responsive_builder UI package.

## [1.0.1] - Readme Updates

Fixed the readme mistakes.

## [1.0.2] - Update Dependencies

Replaced deprecated `builder` param with `create` in ChangeNotifierProvider

## [1.0.3] - Added listen configuration to Provider widget

We can now supply a listen parameter to the super class of the `ProviderWidget` to ensure it's not rebuilt when notifyListeners is called.
