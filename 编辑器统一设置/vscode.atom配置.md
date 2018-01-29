# VSCode and Atom编辑器配置
主要对编码格式化配置，其他随意吧。都使用了prettier来做格式化插件

### VSCode编辑器配置：
```
// 将设置放入此文件中以覆盖默认设置
{
    "editor.fontSize": 14,
    "files.autoSave": "afterDelay",
    "editor.fontFamily": "'Sans Reguler','Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
    "workbench.colorTheme": "Monokai",
    "editor.wordWrapColumn": 250,
    "vetur.format.defaultFormatter.js": "prettier",
    "prettier.eslintIntegration": true,
    "prettier.trailingComma": "all",
    "prettier.singleQuote": true,
    "prettier.arrowParens": "always",
}
```

### Atom编辑器配置：
```
"*":
  "atom-beautify":
    general:
      _analyticsUserId: "59cfe97b-6703-48d1-accb-54f4f7f8808b"
    html: {}
    js:
      default_beautifier: "ESLint Fixer"
      end_of_line: "LF"
      jslint_happy: true
      unescape_strings: true
    vue:
      brace_style: "none"
      break_chained_methods: true
      disabled: true
      end_of_line: "LF"
      end_with_comma: true
      end_with_newline: true
      indent_inner_html: true
      indent_scripts: "keep"
      indent_with_tabs: true
      jslint_happy: true
      keep_array_indentation: true
      keep_function_indentation: true
  "atom-material-ui":
    colors:
      accentColor: "#af0010"
      genAccent: true
      paintCursor: true
    fonts: {}
    tabs:
      compactTabs: true
    ui:
      panelContrast: true
      panelShadows: true
  autosave:
    enabled: true
  core:
    disabledPackages: [
      "symbols-view"
      "vue-format"
      "formatter"
    ]
    packagesWithKeymapsDisabled: [
      "vue-format"
      "formatter"
      "prettier-atom"
    ]
    telemetryConsent: "limited"
    themes: [
      "atom-material-ui"
      "one-dark-syntax"
    ]
  editor:
    fontSize: 15
    invisibles: {}
    preferredLineLength: 100
  "exception-reporting":
    userId: "2afc7a2b-f35f-4760-850e-3dc68a3da39f"
  "js-hyperclick":
    extensions: [
      ".js"
      ".json"
      ".node"
      ".vue"
    ]
    jumpToImport: true
    usePendingPanes: true
  "linter-eslint":
    disableFSCache: true
    disableWhenNoEslintConfig: false
    ignoreFixableRulesWhileTyping: true
    lintHtmlFiles: true
    showRuleIdInMessage: false
  "linter-ui-default":
    panelHeight: 143
    showPanel: true
  minimap:
    plugins:
      "git-diff": true
      "git-diffDecorationsZIndex": 0
  "prettier-atom":
    formatOnSaveOptions: {}
    prettierEslintOptions: {}
    prettierOptions:
      arrowParens: "always"
      jsxBracketSameLine: true
      printWidth: 100
      singleQuote: true
      tabWidth: 2
      trailingComma: "es5"
  "sync-settings":
    personalAccessToken: "7911b9a0d139c156c3bbb2577bca9a721d271468"
  welcome:
    showOnStartup: false
```
