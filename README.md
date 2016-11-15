# TMW tech repo settings
Shared settings for all devs to use in each project

---

## ES2015/ES6
[Babel JS transpiler](https://babeljs.io/)

See our babel config [here](https://github.com/tmwagency/repo-settings/blob/master/package.json#L56-L68)

---

## Use 'xo' for Javascript linting
[xo JS linter](https://github.com/sindresorhus/xo/) ([default rules](https://github.com/sindresorhus/xo/#default-code-style))

We override the defaults by enforcing [dangly-commas](http://eslint.org/docs/rules/comma-dangle) and camelCase file names (js only)

See our xo rules [here](https://github.com/tmwagency/repo-settings/blob/master/package.json#L69-L92)

### Editor plugins
* For Atom: [linter-xo](https://atom.io/packages/linter-xo)
* For Sublime: [SublimeLinter-contrib-xo](https://packagecontrol.io/packages/SublimeLinter-contrib-xo)
* For VS Code: [linter-xo](https://marketplace.visualstudio.com/items?itemName=samverschueren.linter-xo)

---

## Use 'stylelint' for Sass linting
[stylelint CSS linter](http://stylelint.io/). We use [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) as our default rules, see an example [here](https://github.com/stylelint/stylelint-config-standard#example)

See our stylelint rules [here](https://github.com/tmwagency/repo-settings/blob/master/package.json#L93-L129)

### Editor plugins
* For Atom: [linter-stylelint](https://atom.io/packages/linter-stylelint)
* For Sublime: [SublimeLinter-contrib-stylelint](https://packagecontrol.io/packages/SublimeLinter-contrib-stylelint)
* For VS Code: [stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)

---

## EditorConfig
[EditorConfig](http://editorconfig.org/) helps developers define and maintain consistent coding styles between different editors and IDEs. 

See our EditorConfig rules [here](https://github.com/tmwagency/repo-settings/blob/master/.editorconfig)

### Editor plugins
* For Atom: [editorconfig](https://atom.io/packages/editorconfig)
* For Sublime: [EditorConfig](https://packagecontrol.io/packages/EditorConfig)
* For VS Code: [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
* For Visual Studio: [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfigTeam.EditorConfig)

---

## NPM
* [run scripts docs](https://docs.npmjs.com/misc/scripts)
