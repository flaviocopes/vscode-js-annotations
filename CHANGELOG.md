# Changelog

## 0.4.1 - Aug 28, 2018
- [Hotfix] switched jsannotations.hideIfEqual to be on by default

## 0.4.0 - Aug 27, 2018
- [Feature] new config: jsannotations.hideIfEqual - will not display annotation if the name of the argument matches the name of the parameter (configured to be false by default).

## 0.3.3 - Aug 27, 2018
- [Bug] for-of loop iterating through functions could cause incorrect decoration.
- [Bug] callback functions could cause incorrect decorations.

## 0.3.2 - Aug 25, 2018
- [Bug] files using tabs as indentation were misaligning annotation

## 0.3.1 - Aug 24, 2018
- [Hotfix] Updated Readme

## 0.3.0 - Aug 24, 2018
- [Feature] Now supports Typescript

## 0.2.1 - Aug 20, 2018
- [Hotfix] Added keybinding for toggling annotations ('ctrl/cmd+k a' by default)
- [Hotfix] Switched color config to use builtin 'colors' contributes property

## 0.2.0 - Aug 19, 2018
- [Feature] Configuration for enabling / disabling annotations: jsannotations.enabled
- [Feature] Configuration for changing color of annotations on light and dark themes: jsannotations.colors
- [Feature] Command to hide / show annotations: "JS Annotations: Hide / Show Annotations
- [Bug] Fixed to only made decorate run on JS files

## 0.1.0 - Aug 15, 2018
- Initial Release