# React notes

Notes from: https://app.pluralsight.com/player?course=react-big-picture&author=cory-house&name=e20fe73e-099f-4a1d-86a4-0077e941b3ac&clip=4

React is  Library rather than a framework like Angular/Ember
React is lightwieight (35K)
Makes use of JS to create fake HTML rather than HTML to create fake JS Framework specific Syntax (Vue/Ember) - good if you already know JS

Traditioanl WebApps use MVC
*	Model - JS
*	View - HTML
*	Controller - JS
React - all (logic & markup) in same file:
*	JS
*	JSX

Seperation of concerns:
Also instead of 3 diff files for CSS, JS and HTML for your website, a React component file would have:
*   CSS
*   JS
*   HTML
	all in the same file, rather than 3 diff files

Break a page down into small components that are self containted and that you can reason about and test.

Build Step is typically required

Maintain state, can use a number of options:
* Plain React
* Flux
* Redux
* MobX

Notes:
OB: Server Side Rendering of HTML.