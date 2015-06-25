Apple .clang-format
=======================

A .clang-format file as similar as you can get to Apple's code style.

##Installation
1. Download the [ClangFormat-Xcode plugin](https://github.com/travisjeffery/ClangFormat-Xcode)
2. Download this .clang-format file and put it in the root folder of your project.
3. Go to **Edit** > **Clang Format**, choose **File**. It will choose the .clang-format file if it's in the root folder of the project.

## Issues
Please do a pull-request if you spot any attributes that should be altered to make the format more similar to Apple's style. I've added a preview in this README to make it easy to just copy the text if you don't want the hassle of cloning repo or just for quick inspection. Please update the README preview below if you make a pull request that alters the format file.

## Preview

```yaml
---
Language: Cpp
AccessModifierOffset: -2
AlignEscapedNewlinesLeft: false
AlignTrailingComments: true
AllowAllParametersOfDeclarationOnNextLine: true
AllowShortFunctionsOnASingleLine: false
AllowShortIfStatementsOnASingleLine: false
AllowShortLoopsOnASingleLine: false
AlwaysBreakBeforeMultilineStrings: false
AlwaysBreakTemplateDeclarations: false
BinPackParameters: true
BreakBeforeBinaryOperators: false
BreakBeforeBraces: Linux
BreakBeforeTernaryOperators: true
BreakConstructorInitializersBeforeComma: false
ColumnLimit: 0
CommentPragmas: '^ IWYU pragma:'
ConstructorInitializerAllOnOneLineOrOnePerLine: false
ConstructorInitializerIndentWidth: 4
ContinuationIndentWidth: 4
Cpp11BracedListStyle: true
DerivePointerBinding: false
ExperimentalAutoDetectBinPacking: false
IndentCaseLabels: true
IndentFunctionDeclarationAfterType: true
IndentWidth: 4
MaxEmptyLinesToKeep: 2
NamespaceIndentation: None
ObjCSpaceAfterProperty: true
ObjCSpaceBeforeProtocolList: true
ObjCBlockIndentWidth: 4
PenaltyBreakBeforeFirstCallParameter: 19
PenaltyBreakComment: 300
PenaltyBreakFirstLessLess: 120
PenaltyBreakString: 1000
PenaltyExcessCharacter: 1000000
PenaltyReturnTypeOnItsOwnLine: 60
PointerBindsToType: false
SpaceBeforeAssignmentOperators: true
SpaceBeforeParens: ControlStatements
SpaceInEmptyParentheses: false
SpacesBeforeTrailingComments: 1
SpacesInAngles: false
SpacesInContainerLiterals: true
SpacesInCStyleCastParentheses: false
SpacesInParentheses: false
Standard: Cpp11
TabWidth: 8
UseTab: Never
```
## License
MIT
