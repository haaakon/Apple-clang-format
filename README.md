Apple .clang-format
=======================

A .clang-format file as similar as you can get to Apples code style.

##Installation
1. Download the [ClangFormat-Xcode plugin](https://github.com/travisjeffery/ClangFormat-Xcode)
2. Download this .clang-format file and put it in the root folder of your project.
3. Go to Edit - Clang Format, choose File. It will choose the .clang-format file if its in the root folder of the project

## Issues
Please do a pull-request if you spot any attributes that should be altered to make the format more similar to Apples style. I've added a preview in this readme to make it easy just copying the text if you don't want the hassle of cloning repo or just for quick inspection. Please update the readme clangformat preview if you make a pull request for altering the format file.

##Preview

```yaml
---
Language:        Cpp
# BasedOnStyle:  LLVM
AccessModifierOffset: -2
ConstructorInitializerIndentWidth: 4
AlignEscapedNewlinesLeft: false
AlignTrailingComments: true
AllowAllParametersOfDeclarationOnNextLine: true
AllowShortIfStatementsOnASingleLine: false
AllowShortLoopsOnASingleLine: false
AllowShortFunctionsOnASingleLine: false
AlwaysBreakTemplateDeclarations: false
AlwaysBreakBeforeMultilineStrings: false
BreakBeforeBinaryOperators: false
BreakBeforeTernaryOperators: true
BreakConstructorInitializersBeforeComma: false
BinPackParameters: true
ColumnLimit: 115
IndentWidth: 4
ConstructorInitializerAllOnOneLineOrOnePerLine: false
DerivePointerBinding: false
ExperimentalAutoDetectBinPacking: false
IndentCaseLabels: true
MaxEmptyLinesToKeep: 1
NamespaceIndentation: None
ObjCSpaceAfterProperty: true
ObjCSpaceBeforeProtocolList: true
PenaltyBreakBeforeFirstCallParameter: 19
PenaltyBreakComment: 300
PenaltyBreakString: 1000
PenaltyBreakFirstLessLess: 120
PenaltyExcessCharacter: 1000000
PenaltyReturnTypeOnItsOwnLine: 60
PointerBindsToType: false
SpacesBeforeTrailingComments: 1
Cpp11BracedListStyle: true
Standard: Cpp11
TabWidth: 8
UseTab: Never
BreakBeforeBraces: Stroustrup
IndentFunctionDeclarationAfterType: true
SpacesInParentheses: false
SpacesInAngles:  false
SpaceInEmptyParentheses: false
SpacesInCStyleCastParentheses: false
SpacesInContainerLiterals: true
SpaceBeforeAssignmentOperators: true
ContinuationIndentWidth: 4
CommentPragmas:  '^ IWYU pragma:'
SpaceBeforeParens: ControlStatements

...


```
## License
MIT
