## 0.5.41
- Enable linting of `.js` files.
- Extract the release notes into CHANGELOG.md

## 0.5.40
- Add `tslint.autoFixOnSave` setting which enables fixing auto fixable warnings on file save.
- Added support for auto fixes provided by the tslint library.

## 0.5.39
- The status of the TSLint linter is now shown in the status line.
- Add `tslint.nodePath` setting, which enables to load tslint from a different location than the current workspace or the globally installed npm modules`.
- Added command to create an initial `tslint.json` file.
- Added command to show the tslint output channel.

## 0.5.38
- Warnings are now created into a diagnostic collection `tslint` this improves the integration
with tslint warnings generated by a [problem matcher](https://code.visualstudio.com/docs/editor/tasks#_processing-task-output-with-problem-matchers).

## 0.5.35
- Added a command `Fix all auto-fixable problems`.

## 0.5.34
- Add a setting to lint on save only.

## 0.5.33
- Only prompt for installing tslint, when the workspace root includes a `tslint.json` file.

## 0.5.32
- Clear errors when document is closed.

## 0.5.30
- More quick fixes.

## 0.5.25
- Add support for quick fixing some warnings.

## 0.5.23
- Updated to version 2.0 of the vscode language protocol.

## 0.5.21
- Added the setting `tslint.validateWithDefaultConfig`.

## 0.5.17
- Added setting `tslint.validateWithDefaultConfig`.
- Added setting `tslint.ignoreDefinitionFiles`.

## 0.5.15
- Watch for changes in the tslint.json when the file is located outside of the workspace.

## 0.5.13
- Handle the case where a user edits a `tslint.json` configuration file and it is in an intermediate inconsistent state gracefully.

## 0.5.8
- protect against exceptions thrown by tslint.

## 0.5.5
- `tslint.json` is now validated using a JSON schema.
- Diagnostic messages produced by tslint are now tagged with `tslint`.

## 0.5.4
- Added the `tslint.configFile` option.