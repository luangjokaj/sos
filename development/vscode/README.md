# VSCode

### Font - [Fira Code](https://github.com/tonsky/FiraCode)

## Extenstions

```
2gua.rainbow-brackets
alefragnani.Bookmarks
alefragnani.project-manager
bierner.markdown-preview-github-styles
christian-kohler.path-intellisense
clinyong.vscode-css-modules
codezombiech.gitignore
cpylua.language-postcss
cssho.vscode-svgviewer
dbaeumer.vscode-eslint
dmitriy-lodyanov.vscode-stylefmt--pr-320
dsznajder.es7-react-js-snippets
dzannotti.vscode-babel-coloring
eamodio.gitlens
ecmel.vscode-html-css
erichbehrens.pull-request-monitor
esbenp.prettier-vscode
fabiospampinato.vscode-highlight
felipecaputo.git-project-manager
flowtype.flow-for-vscode
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
GitHub.github-vscode-theme
ionutvmi.path-autocomplete
jock.svg
joshpeng.sublime-babel-vscode
jpoissonnier.vscode-styled-components
kamikillerto.vscode-colorize
mhmadhamster.postcss-language
mhutchie.git-graph
mikestead.dotenv
mrmlnc.vscode-apache
mrmlnc.vscode-less
mrorz.language-gettext
ms-vsliveshare.vsliveshare
naumovs.color-highlight
neilding.language-liquid
octref.vetur
oderwat.indent-rainbow
ricard.postcss
shinnn.stylelint
sissel.shopify-liquid
spywhere.guides
stubailo.ignore-gitignore
vscode-icons-team.vscode-icons
whatwedo.twig
wix.vscode-import-cost
Zignd.html-css-class-completion
```

## Configuration

```
{
	"editor.minimap.enabled": true,
	"editor.maxTokenizationLineLength": 5000,
	"files.exclude": {
		"**/tmp": true,
		"**/node_modules": true,
		"**/bower_components": true,
		"**/build": true,
		"**/.git": true,
		"**/.svn": true,
		"**/.hg": true,
		"**/CVS": true,
		"**/.DS_Store": true
	},
	"files.watcherExclude": {
		"**/tmp/**": true,
		"**/node_modules/**": true,
		"**/bower_components/**": true,
		"**/build/**": true
	},
	"editor.insertSpaces": false,
	"editor.renderWhitespace": "all",
	"javascript.referencesCodeLens.enabled": true,
	"javascript.validate.enable": false,
	"editor.cursorStyle": "line",
	"editor.smoothScrolling": true,
	"window.zoomLevel": 0,
	"[markdown]": {
		"editor.formatOnSave": false
	},
	"files.associations": {
		"*.css": "postcss",
		"*.js": "javascriptreact",
		"*.tsx": "typescriptreact"
	},
	"path-intellisense.showHiddenFiles": true,
	"workbench.startupEditor": "newUntitledFile",
	"git.confirmSync": false,
	"emmet.triggerExpansionOnTab": true,
	"editor.wordWrap": "on",
	"git.enableSmartCommit": true,
	"emmet.includeLanguages": {
		"ocaml": "html",
		"reason": "html"
	},
	"gitlens.codeLens.recentChange.enabled": false,
	"gitlens.codeLens.authors.enabled": false,
	"editor.renderIndentGuides": false,
	"projectManager.openInNewWindowWhenClickingInStatusBar": true,
	"terminal.integrated.fontFamily": "Inconsolata for Powerline",
	"flow.useNPMPackagedFlow": true,
	"gitlens.advanced.messages": {
		"suppressCommitHasNoPreviousCommitWarning": true,
		"suppressResultsExplorerNotice": true,
		"suppressShowKeyBindingsNotice": true,
		"suppressWelcomeNotice": true
	},
	"indentRainbow.colors": [
		"rgba(64,64,16,0.3)",
		"rgba(32,64,32,0.3)",
		"rgba(64,32,64,0.3)",
		"rgba(16,48,48,0.3)",
		"rgba(128,32,32,0.3)"
	],
	"git.autofetch": true,
	"gitlens.currentLine.enabled": true,
	"gitlens.hovers.currentLine.enabled": true,
	"gitlens.keymap": "chorded",
	"telemetry.enableTelemetry": false,
	"gitlens.advanced.telemetry.enabled": false,
	"editor.tabSize": 4,
	"editor.fontLigatures": true,
	"editor.fontFamily": "Fira Code",
	"terminal.integrated.rendererType": "dom",
	"postcss.validate": false,
	"html.validate.scripts": false,
	"html.format.enable": false,
	"breadcrumbs.enabled": true,
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"highlight.regexes": {
		"(// ?TODO:?)(.*)": [{
				"overviewRulerColor": "#ffcc00",
				"backgroundColor": "#ffcc00",
				"color": "#1f1f1f",
				"fontWeight": "bold"
			},
			{
				"backgroundColor": "#d9ad00",
				"color": "#1f1f1f"
			}
		],
		"(// ?FIXME:?)(.*)": [{
				"overviewRulerColor": "#ff0000",
				"backgroundColor": "#ff0000",
				"color": "#1f1f1f",
				"fontWeight": "bold"
			},
			{
				"backgroundColor": "#d90000",
				"color": "#1f1f1f"
			}
		],
		"(// )(@\\w+)": [{},
			{
				"color": "#4de0ff"
			}
		]
	},
	"gitlens.views.repositories.files.layout": "tree",
	"gitlens.views.fileHistory.enabled": true,
	"gitlens.views.lineHistory.enabled": true,
	"[postcss]": {
		"editor.defaultFormatter": "dmitriy-lodyanov.vscode-stylefmt--pr-320"
	},
	"diffEditor.ignoreTrimWhitespace": false,
	"workbench.iconTheme": "vscode-icons",
	"workbench.colorTheme": "GitHub Dark",
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": false
	},
	"eslint.debug": true,
	"eslint.format.enable": true,
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"prettier.useTabs": true,
	"extensions.ignoreRecommendations": false,
}
```
