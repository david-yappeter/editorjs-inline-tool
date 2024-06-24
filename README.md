![](https://badgen.net/badge/Editor.js/v2.0/blue)

# Inline Onclick

Create custom inline tool for [Editor.js](https://editorjs.io).

## Installation

Get the package

```shell
yarn add @davidyappeter/editorjs-inline-tool
```

Include module at your application

```javascript
import InlineOnclick from "@davidyappeter/editorjs-inline-tool";
```

### Configuration

`createGenericInlineTool` returns an `InlineTool` for `EditorJS`. The following
options are available:

| Name        | Required |   Type   | Default     | Description                                                                                                                                        |
| :---------- | :------: | :------: | :---------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| sanitize    | `false`  | `object` | `undefined` | Object that defines rules for [automatic sanitizing](https://editorjs.io/tools-api#sanitize).                                                      |
| shortcut    | `false`  | `string` | `undefined` | [Shortcut](https://github.com/codex-team/codex.shortcuts) to apply [Tool's render and inserting behaviour](https://editorjs.io/tools-api#shortcut) |
| tagName     |  `true`  | `string` | `undefined` | text [formatting tag](https://www.w3schools.com/html/html_formatting.asp) (eg. `bold`)                                                             |
| toolboxIcon |  `true`  | `string` | `undefined` | Icon for the tools [inline toolbar](https://editorjs.io/inline-tools-api-1#render)                                                                 |

