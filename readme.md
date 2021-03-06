# How to Run this App
  * Clone repository.
  * Run `npm install` to get deps.
  * Run `npm run dev` to run webpack.
  * Run `npm run server` to run live-server.
  * Run `npm test` to run tests.

# Requirements
We need `node` & `npm`. Command line commands are run inside the project folder. This guide uses npm but should work the same using yarn.

# Objectives
  * Dive deeper into React Router.
  * Learn about the `render` prop for inlining functions inside `Route`.
  * Learn about the `children` prop for inlining functions inside `Route`.
  * Passing "normal" props along to the component rendered by `Route`.
  * Passing `history`, `match` and `location` props to the component rendered by `Route`.
  * Creating sub-routes using `match.path` and `match.url`.
  * Learn about `history.push()`.
  * Learn about `history.replace()`.
  * Learn about the `NavLink` component.
  * Style Links and Navlinks using `styled-components`.
  * Learn about `Switch` component.
  * Learn about `Redirect` component.
  * Learn about `withRouter` HOC.

# Exercises
  * How to pass player into components.
  * How to have something render always but still get history, location and match.
  * Have a `children` component render to the screen whether there is match or not.
  * Have tic tac toe randomly redirect to Home.
  * Have blackjack check for 'authed' in local storage and send you to Home if there isn't one.
  * Style a Navlink using styled-components.
  * Use withRouter to give a component knowledge of history, match and location.
  * Create dynamic subroutes to blackjack and have the links disappear when user clicks link to sub route.