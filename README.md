# ng-prism
Use prism.js to easily highlight code syntax in your Angular application.

### Using transclusion
`<pre ng-prism="css">.example { color: #000; }</pre>`

### Using a binding expression
`<pre ng-prism="css" ng-prism-data="{{ myCode }}"></pre>`

### Using inline
`<pre ng-prism="css" ng-prism-data=".example { color: #000; }"></pre>`